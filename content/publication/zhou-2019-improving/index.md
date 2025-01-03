---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Improving whole-brain neural decoding of fMRI with domain adaptation
subtitle: ''
summary: ''
authors:
- Shuo Zhou
- Christopher R Cox
- Haiping Lu
tags: []
categories: []
date: '2019-10-01'
lastmod: 2021-12-29T13:50:10Z
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
publishDate: '2021-12-29T13:50:09.013946Z'
publication_types:
- '1'
abstract: 'In neural decoding, there has been a growing interest in machine learning on functional magnetic resonance imaging (fMRI). However, the size discrepancy between the whole-brain feature space and the training set poses serious challenges. Simply increasing the number of training examples is infeasible and costly. In this paper, we propose a domain adaptation framework for whole-brain fMRI (DawfMRI) to improve whole-brain neural decoding on target data leveraging source data. DawfMRI consists of two steps: (1) source and target feature adaptation, and (2) source and target classifier adaptation. We evaluate its four possible variations, using a collection of fMRI datasets from OpenfMRI. The results demonstrated that appropriate choices of source domain can help improve neural decoding accuracy for challenging classification tasks. The best-case improvement is   10.47%  (from   77.26%  to   87.73% ). Moreover, visualising and interpreting voxel weights revealed that the adaptation can provide additional insights into neural decoding.'
publication: '*International Workshop on Machine Learning in Medical Imaging (MLMI)*'
links:
- name: Link
  url: https://link.springer.com/chapter/10.1007%2F978-3-030-32692-0_31
- name: Code
  url: https://github.com/sz144/DawfMRI
---
