---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'EcoICA: Skewness-based ICA via eigenvectors of cumulant operator'
subtitle: ''
summary: ''
authors:
- Liyan Song
- Haiping Lu
tags: []
categories: []
date: '2016-11-01'
lastmod: 2021-12-29T13:50:04Z
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
publishDate: '2021-12-29T13:50:03.163770Z'
publication_types:
- '1'
abstract: 'Independent component analysis (ICA) is an important unsupervised learning method. Most popular ICA methods use kurtosis as a metric of non-Gaussianity to maximize, such as FastICA and JADE.However, their assumption of kurtosic sources may not always be satisfied in practice. For weak-kurtosic but skewed sources, kurtosis-based methods could fail while skewness-based methods seem more promising, where skewness is another non-Gaussianity metric measuring the non-symmetry of signals. Partly due to the common assumption of signal symmetry, skewness-based ICA has not been systematically studied in spite of some existing works. In this paper, we take a systematic approach to develop EcoICA, a new skewness-based ICA method for weak-kurtosic but skewed sources. Specifically, we design a new cumulant operator, define its eigenvalues and eigenvectors, reveal their connections with the ICA model to formulate the EcoICA problem, and use Jacobi method to solve it. Experiments on both synthetic and real data show the superior performance of EcoICA over existing kurtosis-based and skewness-based methods for skewed sources. In particular, EcoICA is less sensitive to sample size, noise, and outlier than other methods. Studies on face recognition further confirm the usefulness of EcoICA in classification.'
publication: '*Asian Conference on Machine Learning (ACML)*'
links:
- name: Link
  url: https://proceedings.mlr.press/v63/Song94.html
---
