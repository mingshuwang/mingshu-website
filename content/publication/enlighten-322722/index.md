---
# Documentation: https://docs.hugoblox.com/managing-content/

title: Understanding the protection of privacy when counting subway travelers through
  anonymization
subtitle: ''
summary: ''
authors:
- Nadia Shafaeipour
- Valeriu-Daniel Stanciu
- Maarten van Steen
- Mingshu Wang
tags:
- K-anonymity
- travelers
- privacy preservation
- general data protection regulation
- public transportation.
categories: []
date: '2024-06-01'
lastmod: 2025-07-09T16:26:36+01:00
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
publishDate: '2025-07-09T15:26:36.049690Z'
publication_types:
- "Journal article"
abstract: Public transportation, especially in large cities, is critical for livability.
  Counting passengers as they travel between stations is crucial to establishing and
  maintaining effective transportation systems. Various information and communication
  technologies, such as GPS, Bluetooth, and Wi-Fi, have been used to measure people's
  movements automatically. Regarding public transportation applications, the automated
  fare collection (AFC) system has been widely adopted as a convenient method for
  measuring passengers, mainly because it is relatively easy to identify card owners
  uniquely and, as such, the movements of their card holders. However, there are serious
  concerns regarding privacy infringements when deploying such technologies, to the
  extent that Europe's General Data Protection Regulation has forbidden straightforward
  deployment for measuring pedestrian dynamics unless explicit consent has been provided.
  As a result, privacy-preservation techniques (e.g., anonymization) must be used
  when deploying such systems. Against this backdrop, we investigate to what extent
  a recently developed anonymization technique, known as detection k-anonymity, can
  be adapted to count public transportation travelers while preserving privacy. In
  the case study, we tested our methods with data from Beijing subway trips. Results
  show different scenarios when detection k-anonymity can be effectively applied and
  when it cannot. Due to the complicated relationship between the detection k-anonymity
  parameters, setting the proper parameter values can be difficult, leading to inaccurate
  results. Furthermore, through detection k-anonymity, it is possible to count travelers
  between two locations with high accuracy. However, counting travelers from more
  than two locations leads to more inaccurate results.
publication: '*Computers, Environment and Urban Systems*'
doi: 10.1016/j.compenvurbsys.2024.102091
links:
- name: URL
  url: https://eprints.gla.ac.uk/322722/
---
