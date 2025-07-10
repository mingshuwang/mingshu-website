---
title: "Home"
type: landing          # 用 Page-builder 的 landing 布局

# ===== 页面区块 =====
blocks:

  # --- 个人简介卡片 ---
  - block: people
    id: about-pi
    content:
      user_groups:
        - Homepage      # 与作者 front-matter 完全一致
    design:
      view: card        # card / compact / list
      columns: '1'
      align: center

# 不要再加其他 block，首页就只会渲染上面这一块
---
