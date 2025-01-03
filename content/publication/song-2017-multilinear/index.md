---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Multilinear regression for embedded feature selection with application to fMRI
  analysis
subtitle: ''
summary: ''
authors:
- Xiaonan Song
- Haiping Lu
tags: []
categories: []
date: '2017-02-01'
lastmod: 2021-12-29T13:50:05Z
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
publishDate: '2021-12-29T13:50:05.064406Z'
publication_types:
- '1'
abstract: 'Embedded feature selection is effective when both prediction and interpretation are needed. The Lasso and its extensions are standard methods for selecting a subset of features while optimizing a prediction function. In this paper, we are interested in embedded feature selection for multidimensional data, wherein (1) there is no need to reshape the multidimensional data into vectors and (2) structural information from multiple dimensions are taken into account. Our main contribution is a new method called Regularized multilinear regression and selection (Remurs) for automatically selecting a subset of features while optimizing prediction for multidimensional data. Both nuclear norm and the ℓ1-norm are carefully incorporated to derive a multi-block optimization algorithm with proved convergence. In particular, Remurs is motivated by fMRI analysis where the data are multidimensional and it is important to find the connections of raw brain voxels with functional activities. Experiments on synthetic and real data show the advantages of Remurs compared to Lasso, Elastic Net, and their multilinear extensions.'
publication: '*AAAI Conference on Artificial Intelligence (AAAI)*'
links:
- name: Link
  url: https://ojs.aaai.org/index.php/AAAI/article/view/10871
- name: PDF
  url: https://ojs.aaai.org/index.php/AAAI/article/view/10871/10730
- name: Code
  url: https://uk.mathworks.com/matlabcentral/fileexchange/71204
---
