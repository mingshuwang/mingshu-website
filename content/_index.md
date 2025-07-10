---
title: ""
type: landing          # 告诉 Hugo 这是一个 Landing Page
sections:
  - block: about.biography    # 只要这一个区块
    id: about                 # 给区块取个锚点，方便将来跳转
    content:
      username: Mingshu Wang  # 对应 authors 文件夹名称

#  - block: hero
#    content:
#      title: |
#        Wowchemy
#        Research Group
#      image:
#        filename: welcome.jpg
#      text: |
#        <br>
#        
#        The **Wowchemy Research Group** has been a center of excellence for Artificial Intelligence research, teaching, and practice since its founding in 2016.
  
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 2
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'

  - block: collection
    content:
      title: Latest Publications
      text: ""
      count: 5
      filters:
        folders:
          - publication
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'

  - block: markdown
    id: footer-img          # 格拉背景图
    content:
      title:
      subtitle: ''
      text: ''
    design:
      columns: '1'
  
      background:
        image:
          filename: coders.jpg   # 保持不变
          size: contain          # cover ➜ contain，整图可见且按比例缩放
          position: center
          parallax: false
          text_color_light: true
  
      spacing:                   # 上下保留 40 px 余白
        padding: ['40px','0','40px','0']  # 顺序：上 右 下 左  :contentReference[oaicite:0]{index=0}
  
      css_class: banner-small    # 用你自己的类名，或者直接删掉此行
      # css_style: 'min-height: 350px;'   # 不想写 SCSS 的话，可一行内联


#  可以考虑放一张图在最下面
#  - block: markdown
#    content:
#      title:
#      subtitle: ''
#      text:
#    design:
#      columns: '1'
#      background:
#        image: 
#          filename: coders.jpg
#          filters:
#            brightness: 1
#          parallax: false
#          position: center
#          size: cover
#          text_color_light: true
#      spacing:
#        padding: ['20px', '0', '20px', '0']
#      css_class: fullscreen

---
