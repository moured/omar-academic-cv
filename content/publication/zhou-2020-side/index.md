---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Side information dependence as a regularizer for analyzing human brain conditions
  across cognitive experiments
subtitle: ''
summary: ''
authors:
- Shuo Zhou
- Wenwen Li
- Christopher Cox
- Haiping Lu
tags: []
categories: []
date: '2020-02-01'
lastmod: 2021-12-29T13:50:17Z
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
publishDate: '2021-12-29T13:50:17.058720Z'
publication_types:
- '1'
abstract: 'The increasing of public neuroimaging datasets opens a door to analyzing homogeneous human brain conditions across datasets by transfer learning (TL). However, neuroimaging data are high-dimensional, noisy, and with small sample sizes. It is challenging to learn a robust model for data across different cognitive experiments and subjects. A recent TL approach minimizes domain dependence to learn common cross-domain features, via the Hilbert-Schmidt Independence Criterion (HSIC). Inspired by this approach and the multi-source TL theory, we propose a Side Information Dependence Regularization (SIDeR) learning framework for TL in brain condition decoding. Specifically, SIDeR simultaneously minimizes the empirical risk and the statistical dependence on the domain side information, to reduce the theoretical generalization error bound. We construct 17 brain decoding TL tasks using public neuroimaging data for evaluation. Comprehensive experiments validate the superiority of SIDeR over ten competing methods, particularly an average improvement of 15.6% on the TL tasks with multi-source experiments.'
publication: '*AAAI Conference on Artificial Intelligence (AAAI)*'
links:
- name: Link
  url: https://doi.org/10.1609/aaai.v34i04.6179
- name: PDF
  url: https://ojs.aaai.org/index.php/AAAI/article/view/6179/6035
- name: Code  
  url: https://github.com/sz144/sider
---
