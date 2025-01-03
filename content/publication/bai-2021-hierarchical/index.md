---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Hierarchical clustering split for low-bias evaluation of drug-target interaction
  prediction
subtitle: ''
summary: ''
authors:
- Peizhen Bai
- Filip Miljković
- Yan Ge
- Nigel Greene
- Bino John
- Haiping Lu
tags: []
categories: []
date: '2021-12-02'
lastmod: 2021-12-29T13:49:20Z
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
publishDate: '2021-12-29T13:49:20.010812Z'
publication_types:
- '1'
abstract: 'Drug-target interaction (DTI) prediction is important in drug discovery and chemogenomics studies. Machine learning, particularly deep learning, has advanced this area significantly over the past few years. However, a significant gap between the performance reported in academic papers and that in practical drug discovery settings, e.g. the random-split-based evaluation strategy tends to be too optimistic in estimating the prediction performance in real-world settings. Such performance gap is largely due to hidden data bias in experimental datasets and inappropriate data split. In this paper, we construct a low-bias DTI dataset and study more challenging data split strategies to improve performance evaluation for real-world settings. Specifically, we study the data bias in a popular DTI dataset, BindingDB, and re-evaluate the prediction performance of three state-of-the-art deep learning models using five different data split strategies: random split, cold drug split, scaffold split, and two hierarchical-clustering-based splits. In addition, we comprehensively examine six performance metrics. Our experimental results confirm the overoptimism of the popular random split and show that hierarchical-clustering-based splits are far more challenging and can provide potentially more useful assessment of model generalizability in real-world DTI prediction settings.'
publication: '*IEEE International Conference on Bioinformatics and Biomedicine (BIBM)*'
links:
- name: Link
  url: https://ieeexplore.ieee.org/abstract/document/9669515
- name: PDF
  url: http://staffwww.dcs.shef.ac.uk/people/H.Lu/Publications/LowBiasDTI_BIBM2021.pdf
---
