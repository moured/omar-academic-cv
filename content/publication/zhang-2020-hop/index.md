---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Hop-hop relation-aware graph neural networks
subtitle: ''
summary: ''
authors:
- Li Zhang
- Yan Ge
- Haiping Lu
tags: []
categories: []
date: '2020-12-01'
lastmod: 2021-12-29T13:50:29Z
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
publishDate: '2021-12-29T13:50:28.691243Z'
publication_types:
- '3'
abstract: 'Graph Neural Networks (GNNs) are widely used in graph representation learning. However, most GNN methods are designed for either homogeneous or heterogeneous graphs. In this paper, we propose a new model, Hop-Hop Relation-aware Graph Neural Network (HHR-GNN), to unify representation learning for these two types of graphs. HHR-GNN learns a personalized receptive field for each node by leveraging knowledge graph embedding to learn relation scores between the central node''s representations at different hops. In neighborhood aggregation, our model simultaneously allows for hop-aware projection and aggregation. This mechanism enables the central node to learn a hop-wise neighborhood mixing that can be applied to both homogeneous and heterogeneous graphs. Experimental results on five benchmarks show the competitive performance of our model compared to state-of-the-art GNNs, e.g., up to 13K faster in terms of time cost per training epoch on large heterogeneous graphs.'
publication: '*arXiv preprint arXiv:2012.11147*'
links:
- name: Link
  url: https://arxiv.org/abs/2012.11147
---
