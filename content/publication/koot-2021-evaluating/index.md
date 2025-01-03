---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Evaluating transformers for lightweight action recognition
subtitle: ''
summary: ''
authors:
- Raivo Koot
- Markus Hennerbichler
- Haiping Lu
tags: []
categories: []
date: '2021-11-01'
lastmod: 2021-12-29T13:50:34Z
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
publishDate: '2021-12-29T13:50:34.190688Z'
publication_types:
- '3'
abstract: 'In video action recognition, transformers consistently reach state-of-the-art accuracy. However, many models are too heavyweight for the average researcher with limited hardware resources. In this work, we explore the limitations of video transformers for lightweight action recognition. We benchmark 13 video transformers and baselines across 3 large-scale datasets and 10 hardware devices. Our study is the first to evaluate the efficiency of action recognition models in depth across multiple devices and train a wide range of video transformers under the same conditions. We categorize current methods into three classes and show that composite transformers that augment convolutional backbones are best at lightweight action recognition, despite lacking accuracy. Meanwhile, attention-only models need more motion modeling capabilities and stand-alone attention block models currently incur too much latency overhead. Our experiments conclude that current video transformers are not yet capable of lightweight action recognition on par with traditional convolutional baselines, and that the previously mentioned shortcomings need to be addressed to bridge this gap. Code to reproduce our experiments will be made publicly available.'
publication: '*arXiv preprint arXiv:2111.09641*'
links:
- name: Link
  url: https://arxiv.org/abs/2111.09641
---
