---
# Documentation: https://docs.hugoblox.com/managing-content/

title: 'GeoAggregator: An Efficient Transformer Model for Geo-Spatial Tabular Data'
subtitle: ''
summary: ''
authors:
- Rui Deng
- Ziqi Li
- Mingshu Wang
tags: []
categories: []
date: '2025-01-01'
lastmod: 2025-07-09T16:26:35+01:00
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
publishDate: '2025-07-09T15:26:34.758218Z'
publication_types:
- "paper-conference"
abstract: Modeling geospatial tabular data with deep learning has become a promising
  alternative to traditional statistical and machine learning approaches. However,
  existing deep learning models often face challenges related to scalability and flexibility
  as datasets grow. To this end, this paper introduces GeoAggregator, an efficient
  and lightweight algorithm based on transformer architecture designed specifically
  for geospatial tabular data modeling. GeoAggregators explicitly account for spatial
  autocorrelation and spatial heterogeneity through Gaussian-biased local attention
  and global positional awareness. Additionally, we introduce a new attention mechanism
  that uses the Cartesian product to manage the size of the model while maintaining
  strong expressive power. We benchmark GeoAggregator against spatial statistical
  models, XGBoost, and several state-of-the-art geospatial deep learning methods using
  both synthetic and empirical geospatial datasets. The results demonstrate that GeoAggregators
  achieve the best or second-best performance compared to their competitors on nearly
  all datasets. GeoAggregator's efficiency is underscored by its reduced model size,
  making it both scalable and lightweight. Moreover, ablation experiments offer insights
  into the effectiveness of the Gaussian bias and Cartesian attention mechanism, providing
  recommendations for further optimizing the GeoAggregator's performance.
publication: "*39th Annual AAAI Conference on Artificial Intelligence (AAAI'25)*, (pp. 11572–11580). AAAI Press. https://doi.org/10.1609/aaai.v39i11.33259"
doi: 10.1609/aaai.v39i11.33259
links:
- name: URL
  url: https://eprints.gla.ac.uk/354147/
---
