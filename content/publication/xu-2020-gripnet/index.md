---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'GripNet: Graph information propagation on supergraph for heterogeneous graphs'
subtitle: ''
summary: ''
authors:
- Hao Xu
- Shengqi Sang
- Peizhen Bai
- Laurence Yang
- Haiping Lu
tags: []
categories: []
date: '2020-10-01'
lastmod: 2021-12-29T13:50:24Z
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
publishDate: '2021-12-29T13:50:23.970009Z'
publication_types:
- '3'
abstract: 'Heterogeneous graph representation learning aims to learn low-dimensional vector representations of different types of entities and relations to empower downstream tasks. Existing methods either capture semantic relationships but indirectly leverage node/edge attributes in a complex way, or leverage node/edge attributes directly without taking semantic relationships into account. When involving multiple convolution operations, they also have poor scalability. To overcome these limitations, this paper proposes a flexible and efficient Graph information propagation Network (GripNet) framework. Specifically, we introduce a new supergraph data structure consisting of supervertices and superedges. A supervertex is a semantically-coherent subgraph. A superedge defines an information propagation path between two supervertices. GripNet learns new representations for the supervertex of interest by propagating information along the defined path using multiple layers. We construct multiple large-scale graphs and evaluate GripNet against competing methods to show its superiority in link prediction, node classification, and data integration.'
publication: '*arXiv preprint arXiv:2010.15914*'
links:
- name: Link
  url: https://arxiv.org/abs/2010.15914
- name: Code
  url: https://github.com/NYXFLOWER/GripNet
---
