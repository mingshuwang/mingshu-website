---
title: "Home"
type: landing              # 告诉 Hugo 这里用 Page-builder 模板
blocks:
  - block: people          # ❶ 使用 People 区块渲染作者卡片
    content:               #    content 子字段 = 区块参数
      # block ID 便于 CSS/JS 针对性改样式，可随意取名
      id: "pi-info"        
      user_groups:
        - Principal Investigator   # 必须和作者 front-matter 的 user_groups 完全一致
      # 若你不想按组过滤，可直接删掉 user_groups，People 区块会把站点所有作者都列出来
    design:               # ❷ 版式设计
      view: card          # 可选值：card / compact / list
      columns: '1'        # 单列，等效作者独立页面布局
      align: center
---

# （可选）在上方插入其他块，例如 News / Featured publications …
