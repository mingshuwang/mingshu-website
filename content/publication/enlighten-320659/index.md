---
# Documentation: https://docs.hugoblox.com/managing-content/

title: Graph convolutional networks for street network analysis with a case study
  of urban polycentricity in Chinese cities
subtitle: ''
summary: ''
authors:
- Ding Ma
- Fangning He
- Yang Yue
- Renzhong Guo
- Tianhong Zhao
- Mingshu Wang
tags:
- graph convolutional network; deep learning; street network; urban structure.
categories: []
date: '2024-02-01'
lastmod: 2025-07-09T16:26:41+01:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2025-07-09T15:26:40.550083Z'
publication_types:
- "paper-journal"
abstract: Graph theory effectively explains urban structures via street-street connectivity.
  However, systematic comparisons of street structures across cities remain challenging.
  This study employs graph convolutional networks (GCNs) to analyze street network
  structures. A two-branch GCN was used as the backbone to extract comparable features
  among street networks. The proposed approach was used to examine the structures
  of different urban road networks in a case study of polycentricity prediction across
  298 Chinese cities. The model transformed approximately 4.5-million street segments
  into natural streets to create urban street graphs, which were subsequently analyzed
  to extract local and global embeddings. The extracted embeddings - with a portion
  labeled with a known urban polycentricity score - were used to predict the score
  for each city through a single-layer perceptron (SLP) model. Our results show consistency
  between the predicted polycentricity scores based on the derived street embeddings
  and those based on the population. Thus, the proposed GCN-based method can effectively
  predict the complexity and interconnection of street networks in different cities.
  This innovative integration of GCNs into urban studies demonstrates that deep learning
  techniques can analyze and comprehend the intricate patterns of street networks
  on a large scale.
publication: '*International Journal of Geographical Information Science*'
doi: 10.1080/13658816.2024.2321229
links:
- name: URL
  url: https://eprints.gla.ac.uk/320659/
---
