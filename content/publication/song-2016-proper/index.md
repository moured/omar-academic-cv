---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Proper inner product with mean displacement for gaussian noise invariant ICA
subtitle: ''
summary: ''
authors:
- Liyan Song
- Haiping Lu
tags: []
categories: []
date: '2016-11-01'
lastmod: 2021-12-29T13:50:03Z
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
publishDate: '2021-12-29T13:50:02.373123Z'
publication_types:
- '1'
abstract: 'Independent Component Analysis (ICA) is a classical method for Blind Source Separation (BSS). In this paper, we are interested in ICA in the presence of noise, i.e., the noisy ICA problem. Pseudo-Euclidean Gradient Iteration (PEGI) is a recent cumulant-based method that defines a pseudo Euclidean inner product to replace a quasi-whitening step in Gaussian noise invariant ICA. However, PEGI has two major limitations: 1) the pseudo Euclidean inner product is improper because it violates the positive definiteness of inner product; 2) the inner product matrix is orthogonal by design but it has gross errors or imperfections due to sample-based estimation. This paper proposes a new cumulant-based ICA method named as PIMD to address these two problems. We first define a Proper Inner product (PI) with proved positive definiteness and then relax the centering preprocessing step to a mean displacement (MD) step. Both PI and MD aim to improve the orthogonality of inner product matrix and the recovery of independent components (ICs) in sample-based estimation. We adopt a gradient iteration step to find the ICs for PIMD. Experiments on both synthetic and real data show the respective effectiveness of PI and MD as well as the superiority of PIMD over competing ICA methods. Moreover, MD can improve the performance of other ICA methods as well.'
publication: '*Asian Conference on Machine Learning (ACML)*'
links:
- name: Link
  url: http://proceedings.mlr.press/v63/Song106.html
---
