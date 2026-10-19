---
title: ""                  #这一页其实是主页
type: landing          # 告诉 Hugo 这是一个 Landing Page
sections:
  - block: about.biography    # 只要这一个区块
    id: about                 # 给区块取个锚点，方便将来跳转
    content:
      username: Mingshu Wang  # 对应 authors 文件夹名称
      text: |
        I am a Reader in Geospatial Data Science at the University of Glasgow. My research connects GeoAI, geographical information science and urban analytics, developing spatially aware and explainable methods to understand cities and regions.

        With my [students and collaborators](/people/), I investigate how urban form, infrastructure networks and digital platforms relate to mobility, accessibility, inequality, and economic and environmental outcomes. My work combines machine learning with spatial theory, spatial econometrics and network science, linking methodological development to substantive questions in urban and regional research.
      interests:
        - GeoAI
        - Geographical Information Science
        - Urban Analytics

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
  
  - block: markdown
    id: research-mission
    content:
      title: Research mission
      text: |
        Our mission is to advance GeoAI that connects predictive modelling with explanation grounded in spatial theory. We aim to build transparent, computationally efficient representations of urban and regional systems that help researchers and planners understand spatial inequalities and assess development choices.

        [Explore our research →](/research/)
    design:
      columns: '1'
      spacing:
        padding: ['40px', '0', '40px', '0']

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
      count: 3
      archive:
        enable: true
        text: All publications
        link: /publication/
      filters:
        folders:
          - publication
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title: People behind the research
      subtitle:
      text: |
        Meet the doctoral researchers, visiting scholars and collaborators contributing to our work in GeoAI and urban analytics.

        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'

# 这里可以放一张图
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
