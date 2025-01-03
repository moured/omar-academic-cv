---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Graph node-feature convolution for representation learning
subtitle: ''
summary: ''
authors:
- Li Zhang
- Heda Song
- Haiping Lu
tags: []
categories: []
date: '2018-11-01'
lastmod: 2021-12-29T13:50:13Z
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
publishDate: '2021-12-29T13:50:12.097449Z'
publication_types:
- '3'
abstract: 'Graph convolutional network (GCN) is an emerging neural network approach. It learns new representation of a node by aggregating feature vectors of all neighbors in the aggregation process without considering whether the neighbors or features are useful or not. Recent methods have improved solutions by sampling a fixed size set of neighbors, or assigning different weights to different neighbors in the aggregation process, but features within a feature vector are still treated equally in the aggregation process. In this paper, we introduce a new convolution operation on regular size feature maps constructed from features of a fixed node bandwidth via sampling to get the first-level node representation, which is then passed to a standard GCN to learn the second-level node representation. Experiments show that our method outperforms competing methods in semi-supervised node classification tasks. Furthermore, our method opens new doors for exploring new GCN architectures, particularly deeper GCN models.'
publication: '*arXiv preprint arXiv:1812.00086*'
links:
- name: Link
  url: https://arxiv.org/abs/1812.00086
---
