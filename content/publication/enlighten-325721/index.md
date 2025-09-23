---
# Documentation: https://docs.hugoblox.com/managing-content/

title: A Transformer-Based Model for Effective Representation of Geospatial Data and
  Context
subtitle: ''
summary: ''
authors:
- Rui Deng
- Ziqi Li
- Mingshu Wang
tags: []
categories: []
date: '2024-04-01'
lastmod: 2025-07-09T16:26:39+01:00
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
publishDate: '2025-07-09T15:26:38.521341Z'
publication_types:
- "paper-conference"
abstract: Machine learning (ML) and Artificial Intelligence (AI) models have been
  increasingly adopted for geospatial tasks. However, geospatial data (such as points
  and raster cells) are often influenced by underlying spatial effects, and current
  model designs often lack adequate consideration of these effects. Determining the
  efficient model structure for representing geospatial data and capturing the underlying
  complex spatial and contextual effects still needs to be explored. To address this
  gap, we propose a Transformer-like encoder-decoder architecture to first represent
  geospatial data with respect to their corresponding geospatial context, and then
  decode the representation for task-specific inferences. The encoder consists of
  embedding layers that transform the input location and attributes of geospatial
  data into meaningful embedding vectors. The decoder comprises task-specific neural
  network layers that map the encoder outputs to the final output. Spatial contextual
  effects are measured using explainable artificial intelligence (XAI) methods. We
  evaluate and compare the performance of our model with other model structures on
  both synthetic and real-world datasets for spatial regression and interpolation
  tasks. This work proposes a generalizable approach to better modeling and measuring
  complex spatial contextual effects, potentially contribute to efficient and reliable
  urban analytic applications that require geo-context information.
publication: '*A Transformer-Based Model for Effective Representation of Geospatial Data and Context*, In EGUsphere, EGU General Assembly 2024 (p. 1003). Copernicus Meetings. https://doi.org/10.5194/egusphere-egu24-1003'
doi: 10.5194/egusphere-egu24-1003
links:
- name: URL
  url: https://eprints.gla.ac.uk/325721/
---
