---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Rank-one matrix completion with automatic rank estimation via L1-norm regularization
subtitle: ''
summary: ''
authors:
- Qiquan Shi
- Haiping Lu
- Yiu-Ming Cheung
tags: []
categories: []
date: '2018-10-01'
lastmod: 2021-12-29T13:50:08Z
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
publishDate: '2021-12-29T13:50:08.029456Z'
publication_types:
- '2'
abstract: 'Completing a matrix from a small subset of its entries, i.e., matrix completion is a challenging problem arising from many real-world applications, such as machine learning and computer vision. One popular approach to solve the matrix completion problem is based on low-rank decomposition/factorization. Low-rank matrix decomposition-based methods often require a prespecified rank, which is difficult to determine in practice. In this paper, we propose a novel low-rank decomposition-based matrix completion method with automatic rank estimation. Our method is based on rank-one approximation, where a matrix is represented as a weighted summation of a set of rank-one matrices. To automatically determine the rank of an incomplete matrix, we impose L1-norm regularization on the weight vector and simultaneously minimize the reconstruction error. After obtaining the rank, we further remove the L1-norm regularizer and refine recovery results. With a correctly estimated rank, we can obtain the optimal solution under certain conditions. Experimental results on both synthetic and real-world data demonstrate that the proposed method not only has good performance in rank estimation, but also achieves better recovery accuracy than competing methods.'
publication: '*IEEE Transactions on Neural Networks and Learning Systems*'
links:
- name: Link
  url: https://doi.org/10.1109/TNNLS.2017.2766160
---
