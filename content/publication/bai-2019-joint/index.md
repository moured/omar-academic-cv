---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Joint interaction with context operation for collaborative filtering
subtitle: ''
summary: ''
authors:
- Peizhen Bai
- Yan Ge
- Fangling Liu
- Haiping Lu
tags: []
categories: []
date: '2019-08-01'
lastmod: 2021-12-29T13:50:14Z
featured: true
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
publishDate: '2021-12-29T13:50:13.300015Z'
publication_types:
- '2'
abstract: 'In recommender systems, the classical matrix factorization model for collaborative filtering only considers joint interactions between users and items. In contrast, context-aware recommender systems (CARS) use contexts to improve recommendation performance. Some early CARS models treat user, item and context equally, unable to capture contextual impact accurately. More recent models perform context operations on users and items separately, leading to “double-counting” of contextual information. This paper proposes a new model, Joint Interaction with Context Operation (JICO), to integrate the joint interaction model with the context operation model, via two layers. The joint interaction layer models interactions between users and items via an interaction tensor. The context operation layer captures contextual information via a contextual operating tensor. We evaluate JICO on four datasets and conduct novel studies, including varying contextual influence and time split recommendation. JICO consistently outperforms competing methods, while providing many useful insights to assist further analysis.'
publication: '*Pattern Recognition*'
links:
- name: Link
  url: https://doi.org/10.1016/j.patcog.2018.12.003
- name: PDF
  url: https://eprints.whiterose.ac.uk/140731/8/JICO_PR18.pdf
---
