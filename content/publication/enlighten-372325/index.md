---
# Documentation: https://docs.hugoblox.com/managing-content/

title: Do foundation models work for geospatial tabular data? An investigation
  of TabPFN and a proposed enhancement based on geospatial sparse attention
subtitle: ''
summary: ''
authors:
- Rui Deng
- Ziqi Li
- Mingshu Wang
tags:
- Tabular foundation model
- TabPFN
- geospatial tabular data
- geospatial sparse attention
categories: []
date: '2026-06-29'
lastmod: 2026-07-08T19:00:00+01:00
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
publishDate: '2026-06-29T00:00:00Z'
publication_types:
- "article-journal"
abstract: Large-scale pretrained foundation models have transformed the machine learning paradigm. However, their applicability to Geospatial Tabular Data (GTD), particularly for regression tasks, remains poorly understood. This study systematically investigated TabPFN, a recent tabular foundation model, across synthetic data-generating processes and real-world geospatial regression tasks. We showed that while TabPFN generally outperforms state-of-the-art baselines, its performance degrades on large datasets and under strong, localised spatial dependence. To address these limitations, we proposed Geospatial Sparse Attention (GSA), a spatially informed inference strategy that injects geospatial inductive bias into the off-the-shelf TabPFN framework. The resulting model, TabPFN-GSA, prunes redundant attention calculations to better balance local and global spatial effects while improving scalability to large datasets. Empirical results showed that TabPFN-GSA delivers more accurate and robust predictions, particularly for large-scale GTD. Theoretically, this work advances our understanding of the strengths and limits of tabular foundation models in spatial contexts. Methodologically, it offers TabPFN-GSA, a principled, spatially explicit bridge between classical spatial modelling and modern foundation models.
publication: '*International Journal of Geographical Information Science*, 1-38. https://doi.org/10.1080/13658816.2026.2691066'
doi: 10.1080/13658816.2026.2691066
links:
- name: URL
  url: https://doi.org/10.1080/13658816.2026.2691066
---
