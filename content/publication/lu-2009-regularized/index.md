---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Regularized common spatial patterns with generic learning for EEG signal classification
subtitle: ''
summary: ''
authors:
- Haiping Lu
- Konstantinos N Plataniotis
- Anastasios N Venetsanopoulos
tags: []
categories: []
date: '2009-09-01'
lastmod: 2021-12-29T13:49:34Z
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
publishDate: '2021-12-29T13:49:33.397878Z'
publication_types:
- '1'
abstract: 'The common spatial patterns (CSP) algorithm is commonly used to extract discriminative spatial filters for the classification of electroencephalogram (EEG) signals in the context of brain-computer interfaces (BCIs). However, CSP is based on a sample-based covariance matrix estimation. Therefore, its performance is limited when the number of available training samples is small. In this paper, the CSP method is considered in such a small-sample setting. We propose a regularized common spatial patterns (R-CSP) algorithm by incorporating the principle of generic learning. The covariance matrix estimation in R-CSP is regularized through two regularization parameters to increase the estimation stability while reducing the estimation bias due to limited number of training samples. The proposed method is tested on data set IVa of the third BCI competition and the results show that R-CSP can outperform the classical CSP algorithm by 8.5% on average. Moreover, the regularization introduced is particularly effective in the small-sample setting.'
publication: '*Annual International Conference of the IEEE Engineering in Medicine
  and Biology Society (EMBC)*'
links:
- name: Link
  url: https://doi.org/10.1109/IEMBS.2009.5332554
- name: Code
  url: http://www.mathworks.com/matlabcentral/fileexchange/35734
---
