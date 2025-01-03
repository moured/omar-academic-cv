---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Regularized common spatial pattern with aggregation for EEG classification
  in small-sample setting
subtitle: ''
summary: ''
authors:
- Haiping Lu
- How-Lung Eng
- Cuntai Guan
- Konstantinos N Plataniotis
- Anastasios N Venetsanopoulos
tags: []
categories: []
date: '2010-12-01'
lastmod: 2021-12-29T13:49:37Z
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
publishDate: '2021-12-29T13:49:36.818083Z'
publication_types:
- '2'
abstract: 'Common spatial pattern (CSP) is a popular algorithm for classifying electroencephalogram (EEG) signals in the context of brain-computer interfaces (BCIs). This paper presents a regularization and aggregation technique for CSP in a small-sample setting (SSS). Conventional CSP is based on a sample-based covariance-matrix estimation. Hence, its performance in EEG classification deteriorates if the number of training samples is small. To address this concern, a regularized CSP (R-CSP) algorithm is proposed, where the covariance-matrix estimation is regularized by two parameters to lower the estimation variance while reducing the estimation bias. To tackle the problem of regularization parameter determination, R-CSP with aggregation (R-CSP-A) is further proposed, where a number of R-CSPs are aggregated to give an ensemble-based solution. The proposed algorithm is evaluated on data set IVa of BCI Competition III against four other competing algorithms. Experiments show that R-CSP-A significantly outperforms the other methods in average classification performance in three sets of experiments across various testing scenarios, with particular superiority in SSS.'
publication: '*IEEE Transactions on Biomedical Engineering*'
links:
- name: Link
  url: https://doi.org/10.1109/TBME.2010.2082540
- name: Code
  url: http://www.mathworks.com/matlabcentral/fileexchange/35734
---
