---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: A feature-importance-aware and robust aggregator for GCN
subtitle: ''
summary: ''
authors:
- Li Zhang
- Haiping Lu
tags: []
categories: []
date: '2020-10-01'
lastmod: 2021-12-29T13:50:23Z
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
publishDate: '2021-12-29T13:50:22.758767Z'
publication_types:
- '1'
abstract: 'Neighborhood aggregation is a key step in Graph Convolutional Networks (GCNs) for graph representation learning. Two commonly used aggregators, sum and mean, are designed with the homophily assumption that connected nodes are likely to share the same label. However, real-world graphs are noisy and adjacent nodes do not necessarily imply similarity.Learnable aggregators are proposed in Graph Attention Network (GAT) and Learnable Graph Convolutional Layer (LGCL). However, GAT considers node importance but not the importance of different features. The convolution aggregator in LGCL considers feature importance but it can not directly operate on graphs due to the irregular connectivity and lack of orderliness. In this paper, we firstly unify the current learnable aggregators in a framework: Learnable Aggregator for GCN (LA-GCN) by introducing a shared auxiliary model that provides a customized schema in neighborhood aggregation. Under this framework, we propose a new model called LA-GCNMask consisting of a new aggregator function,mask aggregator. The auxiliary model learns a specific mask for each neighbor of a given node, allowing both node-level and feature-level attention. This mechanism learns to assign different importance to both nodes and features for prediction, which provides interpretable explanations for prediction and increases the model robustness. Experiments on seven graphs for node classification and graph classification tasks show that LA-GCNMask outperforms the state-of-the-art methods. Moreover, our aggregator can identify both the important nodes and node features simultaneously, which provides a quantified understanding of the relationship between input nodes and the prediction. We further conduct experiments on noisy graphs to evaluate the robustness of our model. Experiments show that LA-GCNMask consistently outperforms the state-of-the-art methods, with up to 15% improvements in terms of accuracy compared to the second best.'
publication: '*ACM International Conference on Information and Knowledge Management (CIKM)*'
links:
- name: Link
  url: https://dl.acm.org/doi/abs/10.1145/3340531.3411983
- name: PDF
  url: https://eprints.whiterose.ac.uk/164494/1/LAGCN_CIKM20.pdf
- name: PyTorch Code
  url: https://github.com/asarigun/la-gcn-pytorch
- name: TensorFlow Code
  url: https://github.com/asarigun/la-gcn-tensorflow
---
