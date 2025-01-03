---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Feature extraction for incomplete data via low-rank tensor decomposition with
  feature regularization
subtitle: ''
summary: ''
authors:
- Qiquan Shi
- Yiu-Ming Cheung
- Qibin Zhao
- Haiping Lu
tags: []
categories: []
date: '2019-06-01'
lastmod: 2021-12-29T13:50:11Z
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
publishDate: '2021-12-29T13:50:10.102667Z'
publication_types:
- '2'
abstract: '
Multidimensional data (i.e., tensors) with missing entries are common in practice. Extracting features from incomplete tensors is an important yet challenging problem in many fields such as machine learning, pattern recognition, and computer vision. Although the missing entries can be recovered by tensor completion techniques, these completion methods focus only on missing data estimation instead of effective feature extraction. To the best of our knowledge, the problem of feature extraction from incomplete tensors has yet to be well explored in the literature. In this paper, we therefore tackle this problem within the unsupervised learning environment. Specifically, we incorporate low-rank tensor decomposition with feature variance maximization (TDVM) in a unified framework. Based on orthogonal Tucker and CP decompositions, we design two TDVM methods, TDVM-Tucker and TDVM-CP, to learn low-dimensional features viewing the core tensors of the Tucker model as features and viewing the weight vectors of the CP model as features. TDVM explores the relationship among data samples via maximizing feature variance and simultaneously estimates the missing entries via low-rank Tucker/CP approximation, leading to informative features extracted directly from observed entries. Furthermore, we generalize the proposed methods by formulating a general model that incorporates feature regularization into low-rank tensor approximation. In addition, we develop a joint optimization scheme to solve the proposed methods by integrating the alternating direction method of multipliers with the block coordinate descent method. Finally, we evaluate our methods on six real-world image and video data sets under a newly designed multiblock missing setting. The extracted features are evaluated in face recognition, object/action classification, and face/gait clustering. Experimental results demonstrate the superior performance of the proposed methods compared with the state-of-the-art approaches.'
publication: '*IEEE Transactions on Neural Networks and Learning Systems*'
links:
- name: Link
  url: https://doi.org/10.1109/TNNLS.2018.2873655
---
