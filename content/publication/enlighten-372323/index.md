---
# Documentation: https://docs.hugoblox.com/managing-content/

title: "Zero-shot traffic flow prediction with foundation models: a comparison with deep learning approaches"
subtitle: ''
summary: ''
authors:
- Yue Li
- Qunshan Zhao
- Mingshu Wang
tags:
- Traffic flow prediction
- foundation models
- zero-shot prediction
- deep learning
- time-series prediction
categories: []
date: '2026-05-04'
lastmod: 2026-05-04T00:00:00+00:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

projects: []
publishDate: '2026-05-04T00:00:00Z'
publication_types:
- "Paper-Journal"
abstract: Traffic flow prediction plays an important role in managing urban transportation systems, helping to reduce congestion and improve road safety. Although existing deep learning models improve their predictive accuracy with complex architectures, they require large datasets for task-specific training. Recently, the rapidly developed foundation models have shown outstanding performance in time series prediction. Motivated by the development, we apply two foundation models, Lag-Llama and Chronos, for zero-shot traffic flow prediction and compare their accuracy with that of deep learning models. Our results show that foundation models outperform deep learning models in traffic flow prediction under both normal conditions and disruptive events. Unlike deep learning models, which require large-scale historical data and extensive training time for each task, pre-trained foundation models can be directly applied to datasets with varying data sizes, traffic dynamics, and context lengths. We also find that foundation models with longer context lengths and larger model sizes achieve higher prediction accuracy but require increased inference times. Selecting an appropriate foundation model is also crucial—models trained on a comprehensive dataset are more likely to achieve superior zero-shot performance, making them a practical and efficient choice for real-world traffic prediction applications.
publication: '*Scientific Reports* (2026). https://doi.org/10.1038/s41598-026-50464-8'
doi: 10.1038/s41598-026-50464-8
links:
- name: URL
  url: https://doi.org/10.1038/s41598-026-50464-8
---