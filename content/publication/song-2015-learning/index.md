---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Learning tensor-based features for whole-brain fMRI classification
subtitle: ''
summary: ''
authors:
- Xiaonan Song
- Lingnan Meng
- Qiquan Shi
- Haiping Lu
tags: []
categories: []
date: '2015-10-01'
lastmod: 2021-12-29T13:49:58Z
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
publishDate: '2021-12-29T13:49:57.845630Z'
publication_types:
- '1'
abstract: 'This paper presents a novel tensor-based feature learning approach for whole-brain fMRI classification. Whole-brain fMRI data have high exploratory power, but they are challenging to deal with due to large numbers of voxels. A critical step for fMRI classification is dimensionality reduction, via feature selection or feature extraction. Most current approaches perform voxel selection based on feature selection methods. In contrast, feature extraction methods, such as principal component analysis (PCA), have limited usage on whole brain due to the small sample size problem and limited interpretability. To address these issues, we propose to directly extract features from natural tensor (rather than vector) representations of whole-brain fMRI using multilinear PCA (MPCA), and map MPCA bases to voxels for interpretability. Specifically, we extract low-dimensional tensors by MPCA, and then select a number of MPCA features according to the captured variance or mutual information as the input to SVM. To provide interpretability, we construct a mapping from the selected MPCA bases to raw voxels for localizing discriminating regions. Quantitative evaluations on challenging multiclass tasks demonstrate the superior performance of our proposed methods against the state-of-the-art, while qualitative analysis on localized discriminating regions shows the spatial coherence and interpretability of our mapping.'
publication: '*International Conference on Medical Image Computing and Computer-Assisted
  Intervention (MICCAI)*'
links:
- name: Link
  url: https://link.springer.com/chapter/10.1007/978-3-319-24553-9_75
---
