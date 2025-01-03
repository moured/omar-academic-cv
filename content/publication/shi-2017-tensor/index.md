---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Tensor rank estimation and completion via CP-based nuclear norm
subtitle: ''
summary: ''
authors:
- Qiquan Shi
- Haiping Lu
- Yiu-ming Cheung
tags: []
categories: []
date: '2017-11-01'
lastmod: 2021-12-29T13:50:07Z
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
publishDate: '2021-12-29T13:50:06.830742Z'
publication_types:
- '1'
abstract: 'Tensor completion (TC) is a challenging problem of recovering missing entries of a tensor from its partial observation. One main TC approach is based on CP/Tucker decomposition. However, this approach often requires the determination of a tensor rank a priori. This rank estimation problem is difficult in practice. Several Bayesian solutions have been proposed but they often under/over-estimate the tensor rank while being quite slow. To address this problem of rank estimation with missing entries, we view the weight vector of the orthogonal CP decomposition of a tensor to be analogous to the vector of singular values of a matrix. Subsequently, we define a new CP-based tensor nuclear norm as the $L_1$-norm of this weight vector. We then propose Tensor Rank Estimation based on $L_1$-regularized orthogonal CP decomposition (TREL1) for both CP-rank and Tucker-rank. Specifically, we incorporate a regularization with CP-based tensor nuclear norm when minimizing the reconstruction error in TC to automatically determine the rank of an incomplete tensor. Experimental results on both synthetic and real data show that: 1) Given sufficient observed entries, TREL1 can estimate the true rank (both CP-rank and Tucker-rank) of incomplete tensors well; 2) The rank estimated by TREL1 can consistently improve recovery accuracy of decomposition-based TC methods; 3) TREL1 is not sensitive to its parameters in general and more efficient than existing rank estimation methods.'
publication: '*ACM International Conference on Information and Knowledge Management (CIKM)*'
links:
- name: Link
  url: https://dl.acm.org/doi/10.1145/3132847.3132945
---
