---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Multilinear Subspace Learning for Face and Gait Recognition
subtitle: ''
summary: ''
authors:
- Haiping Lu
tags: []
categories: []
date: '2008-08-01'
lastmod: 2021-12-29T13:49:40Z
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
publishDate: '2021-12-29T13:49:39.947771Z'
publication_types:
- '7'
abstract: 'Face and gait recognition problems are challenging due to largely varying appearances, highly complex pattern distributions, and insufficient training samples. This dissertation focuses on multilinear subspace learning for face and gait recognition, where low-dimensional representations are learned directly from tensorial face or gait objects. 
<br><br>
This research introduces a unifying multilinear subspace learning framework for systematic treatment of the multilinear subspace learning problem. Three multilinear projections are categorized according to the input-output space mapping as: vector-to-vector projection, tensor-to-tensor projection, and tensor-to-vector projection. Techniques for subspace learning from tensorial data are then proposed and analyzed. Multilinear principal component analysis (MPCA) seeks a tensor-to-tensor projection that maximizes the variation captured in the projected space, and it is further combined with linear discriminant analysis and boosting for better recognition performance. Uncorrelated MPCA (UMPCA) solves for a tensor-to-vector projection that maximizes the captured variation in the projected space while enforcing the zero-correlation constraint. Uncorrelated multilinear discriminant analysis (UMLDA) aims to produce uncorrelated features through a tensor-to-vector projection that maximizes a ratio of the between-class scatter over the within-class scatter defined in the projected space. Regularization and aggregation are incorporated in the UMLDA solution for enhanced performance. 
<br><br>
Experimental studies and comparative evaluations are presented and analyzed on the PIE and FERET face databases, and the USF gait database. The results indicate that the MPCA-based solution has achieved the best overall performance in various learning scenarios, the UMLDA-based solution has produced the most stable and competitive results with the same parameter setting, and the UMPCA algorithm is effective in unsupervised learning in low-dimensional subspace. Besides advancing the state-of-the-art of multilinear subspace learning for face and gait recognition, this dissertation also has potential impact in both the development of new multilinear subspace learning algorithms and other applications involving tensor objects.'
publication: ''
links:
- name: Link
  url: https://tspace.library.utoronto.ca/handle/1807/16750
---
