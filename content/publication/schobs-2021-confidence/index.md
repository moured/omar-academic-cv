---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Confidence-quantifying landmark localisation for cardiac MRI
subtitle: ''
summary: ''
authors:
- Lawrence Schobs
- Shuo Zhou
- Marcella Cogliano
- Andrew J Swift
- Haiping Lu
tags: []
categories: []
date: '2021-04-01'
lastmod: 2021-12-29T13:50:26Z
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
publishDate: '2021-12-29T13:50:25.824328Z'
publication_types:
- '1'
abstract: 'Landmark localisation in medical imaging has achieved great success using deep encoder-decoder style networks to regress heatmap images centered around the target landmarks. However, these networks are large and computationally expensive. Moreover, their clinical use often requires human interaction, opening the door for manual correction of low confidence predictions. We propose PHD-Net: a lightweight, multi-task Patch-based network combining Heatmap and Displacement regression. We design a simple Candidate Smoothing strategy to fuse its two-task outputs, generating the final prediction with quantified confidence. We evaluate PHD-Net on hundreds of Short Axis and Four Chamber cardiac MRIs, showing promising results.'
publication: '*IEEE International Symposium on Biomedical Imaging (ISBI)*'
links:
- name: Link
  url: https://doi.org/10.1109/ISBI48211.2021.9433895
---
