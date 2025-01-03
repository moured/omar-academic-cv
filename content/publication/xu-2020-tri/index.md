---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Tri-graph information propagation for polypharmacy side effect prediction
subtitle: ''
summary: ''
authors:
- Hao Xu
- Shengqi Sang
- Haiping Lu
tags: []
categories: []
date: '2019-12-01'
lastmod: 2021-12-29T13:50:16Z
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
publishDate: '2021-12-29T13:50:16.045253Z'
publication_types:
- '1'
abstract: 'The use of drug combinations often leads to polypharmacy side effects (POSE). A recent method formulates POSE prediction as a link prediction problem on a graph of drugs and proteins, and solves it with Graph Convolutional Networks (GCNs). However, due to the complex relationships in POSE, this method has high computational cost and memory demand. This paper proposes a flexible Tri-graph Information Propagation (TIP) model that operates on three subgraphs to learn representations progressively by propagation from protein-protein graph to drug-drug graph via protein-drug graph. Experiments show that TIP improves accuracy by 7%+, time efficiency by 83×, and space efficiency by 3×.'
publication: '*NeurIPS Workshop on Graph Representation Learning*'
links:
- name: Link
  url: https://arxiv.org/abs/2001.10516
- name: PDF  
  url: https://grlearning.github.io/papers/94.pdf
- name: Code
  url: https://github.com/NYXFLOWER/TIP  
---
