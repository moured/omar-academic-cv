---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: A full-body layered deformable model for automatic model-based gait recognition
subtitle: ''
summary: ''
authors:
- Haiping Lu
- Konstantinos N Plataniotis
- Anastasios N Venetsanopoulos
tags: []
categories: []
date: '2008-01-01'
lastmod: 2021-12-29T13:49:30Z
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
publishDate: '2021-12-29T13:49:29.315162Z'
publication_types:
- '2'
abstract: 'This paper proposes a full-body layered deformable model (LDM) inspired by manually labeled silhouettes for automatic model-based gait recognition from part-level gait dynamics in monocular video sequences. The LDM is defined for the fronto-parallel gait with 22 parameters describing the human body part shapes (widths and lengths) and dynamics (positions and orientations). There are four layers in the LDM and the limbs are deformable. Algorithms for LDM-based human body pose recovery are then developed to estimate the LDM parameters from both manually labeled and automatically extracted silhouettes, where the automatic silhouette extraction is through a coarse-to-fine localization and extraction procedure. The estimated LDM parameters are used for model-based gait recognition by employing the dynamic time warping for matching and adopting the combination scheme in AdaBoost.M2. While the existing model-based gait recognition approaches focus primarily on the lower limbs, the estimated LDM parameters enable us to study full-body model-based gait recognition by utilizing the dynamics of the upper limbs, the shoulders and the head as well. In the experiments, the LDM-based gait recognition is tested on gait sequences with differences in shoe-type, surface, carrying condition and time. The results demonstrate that the recognition performance benefits from not only the lower limb dynamics, but also the dynamics of the upper limbs, the shoulders and the head. In addition, the LDM can serve as an analysis tool for studying factors affecting the gait under various conditions.'
publication: '*EURASIP Journal on Advances in Signal Processing*'
links:
- name: Link
  url: https://doi.org/10.1155/2008/261317
---
