---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Semi-orthogonal multilinear PCA with relaxed start
subtitle: ''
summary: ''
authors:
- Qiquan Shi
- Haiping Lu
tags: []
categories: []
date: '2015-07-01'
lastmod: 2021-12-29T13:49:57Z
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
publishDate: '2021-12-29T13:49:57.017498Z'
publication_types:
- '1'
abstract: 'Principal component analysis (PCA) is an unsupervised method for learning low-dimensional features with orthogonal projections. Multilinear PCA methods extend PCA to deal with multidimensional data (tensors) directly via tensor-to-tensor projection or tensor-to-vector projection (TVP). However, under the TVP setting, it is difficult to develop an effective multilinear PCA method with the orthogonality constraint. This paper tackles this problem by proposing a novel Semi-Orthogonal Multilinear PCA (SO-MPCA) approach. SO-MPCA learns low-dimensional features directly from tensors via TVP by imposing the orthogonality constraint in only one mode. This formulation results in more captured variance and more learned features than full orthogonality. For better generalization, we further introduce a relaxed start (RS) strategy to get SO-MPCA-RS by fixing the starting projection vectors, which increases the bias and reduces the variance of the learning model. Experiments on both face (2D) and gait (3D) data demonstrate that SO-MPCA-RS outperforms other competing algorithms on the whole, and the relaxed start strategy is also effective for other TVP-based PCA methods.'
publication: '*International Joint Conference on Artificial Intelligence (IJCAI)*'
links:
- name: Link
  url: https://dl.acm.org/doi/10.5555/2832747.2832780
- name: PDF
  url: https://www.ijcai.org/Proceedings/15/Papers/535.pdf
- name: Code
  url:  http://staffwww.dcs.shef.ac.uk/people/H.Lu/CodeData/SO_MPCA_RS.m 
---
