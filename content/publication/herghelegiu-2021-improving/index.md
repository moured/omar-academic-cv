---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Improving Negative Sampling in Graph Neural Networks for Predicting Drug-Drug
  Interactions
subtitle: ''
summary: ''
authors:
- Alexandra Herghelegiu
- Haiping Lu
tags: []
categories: []
date: '2021-12-01'
lastmod: 2022-02-16T10:45:28Z
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
publishDate: '2022-02-16T10:45:21.341899Z'
publication_types:
- '1'
abstract: 'Predicting drug-drug interactions (DDIs) becomes an increasingly important problem in the computational domain, due to the acceleration of drug discovery and the high costs of solving this task through in vitro experiments. It can be modelled as a link prediction task on a DDIs network, where each node represents a drug and each link represents a meaningful interaction between a pair of drugs. Graph Neural Networks (GNNs) have achieved state-of-the-art results in node classification and graph classification and consequently there is an increasing interest into their application on link prediction. The well-established GNN-based encoder-decoder framework requires negative links (i.e. non-interactions) for training, as it is performed in a supervised fashion. Most of the current DDI datasets do not provide laboratory-confirmed negative interactions (i.e. non-interacting pairs of drugs) and so negative sampling from the unobserved links becomes an exclusively computational task.There is a lack of research investigating the quality and importance of negative sampling techniques when predicting on homogeneous graphs. This paper focuses on improving negative sampling in GNNs on a homogeneous drug-drug interaction graph. An analysis into the effect of negative sampling on predicting DDIs in such a network is carried out and current approaches are formalised and tested. Following this, LANS, a novel Loss-based Adaptive Negative Sampling technique, is introduced. The lightweight LANS method achieves an increase in performance of 16.49% in the Hits@20 metric without adding any trainable parameters to the architecture. Finally, some of its limitations are identified and potential improvements are proposed.'
publication: '*IEEE International Conference on Bioinformatics and Biomedicine (BIBM)*'
links:
- name: Link
  url: https://ieeexplore.ieee.org/abstract/document/9669483
- name: PDF
  url: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9669483
---
