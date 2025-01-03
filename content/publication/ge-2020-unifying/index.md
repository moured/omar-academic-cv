---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Unifying homophily and heterophily network transformation via motifs
subtitle: ''
summary: ''
authors:
- Yan Ge
- Jun Ma
- Li Zhang
- Haiping Lu
tags: []
categories: []
date: '2020-12-01'
lastmod: 2021-12-29T13:50:25Z
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
publishDate: '2021-12-29T13:50:24.823188Z'
publication_types:
- '3'
abstract: 'Higher-order proximity (HOP) is fundamental for most network embedding methods due to its significant effects on the quality of node embedding and performance on downstream network analysis tasks. Most existing HOP definitions are based on either homophily to place close and highly interconnected nodes tightly in embedding space or heterophily to place distant but structurally similar nodes together after embedding. In real-world networks, both can co-exist, and thus considering only one could limit the prediction performance and interpretability. However, there is no general and universal solution that takes both into consideration. In this paper, we propose such a simple yet powerful framework called homophily and heterophliy preserving network transformation (H2NT) to capture HOP that flexibly unifies homophily and heterophily. Specifically, H2NT utilises motif representations to transform a network into a new network with a hybrid assumption via micro-level and macro-level walk paths. H2NT can be used as an enhancer to be integrated with any existing network embedding methods without requiring any changes to latter methods. Because H2NT can sparsify networks with motif structures, it can also improve the computational efficiency of existing network embedding methods when integrated. We conduct experiments on node classification, structural role classification and motif prediction to show the superior prediction performance and computational efficiency over state-of-the-art methods. In particular, DeepWalk-based H2 NT achieves 24% improvement in terms of precision on motif prediction, while reducing 46% computational time compared to the original DeepWalk.'
publication: '*arXiv preprint arXiv:2012.11400*'
links:
- name: Link
  url: https://arxiv.org/abs/2012.11400
---
