---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Mixed-order spectral clustering for complex networks
subtitle: ''
summary: ''
authors:
- Yan Ge
- Pan Peng
- Haiping Lu
tags: []
categories: []
date: '2021-09-01'
lastmod: 2021-12-29T13:50:27Z
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
publishDate: '2021-12-29T13:50:26.621126Z'
publication_types:
- '2'
abstract: 'Spectral clustering (SC) is a popular approach for gaining insights from complex networks. Conventional SC focuses on second-order structures (e.g. edges) without direct consideration of higher-order structures (e.g. triangles). This has motivated SC extensions that directly consider higher-order structures. However, both approaches are limited to considering a single order. To address this issue, this paper proposes a novel Mixed-Order Spectral Clustering (MOSC) framework to model both second-order and third-order structures simultaneously. To model mixed-order structures, we propose two new methods based on Graph Laplacian (GL) and Random Walks (RW). MOSC-GL combines edge and triangle adjacency matrices, with theoretical performance guarantee. MOSC-RW combines first-order and second-order random walks for a probabilistic interpretation. Moreover, we design mixed-order cut criteria to enable existing SC methods to preserve mixed-order structures, and develop new mixed-order evaluation metrics for structure-level evaluation. Experiments on community detection and superpixel segmentation show (1) the superior performance of the MOSC methods over existing SC methods, (2) enhanced performance of conventional SC due to mixed-order cut criteria, and (3) new insights of output clusters offered by the mixed-order evaluation metrics.'
publication: '*Pattern Recognition*'
links:
- name: Link
  url: https://doi.org/10.1016/j.patcog.2021.107964
- name: PDF
  url: http://staffwww.dcs.shef.ac.uk/people/H.Lu/Publications/MOSC_PR21.pdf
- name: Code
  url: https://bitbucket.org/Yan_Sheffield/mosc/src/master/  
---
