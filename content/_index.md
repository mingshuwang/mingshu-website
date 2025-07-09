---
title: "Home"
type: landing            # 告诉 Hugo 用 Page-builder

blocks:
  - block: people        # 使用 People 区块显示作者卡片
    content:
      user_groups:
        - Homepage       # 必须与上一步的组名一致
    design:
      view: card         # card / compact / list 都行
      columns: '1'       # 单列，版式跟作者页一样
      align: center
---
