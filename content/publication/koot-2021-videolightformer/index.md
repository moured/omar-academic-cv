---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'VideoLightFormer: Lightweight action recognition using transformers'
subtitle: ''
summary: ''
authors:
- Raivo Koot
- Haiping Lu
tags: []
categories: []
date: '2021-07-01'
lastmod: 2021-12-29T13:50:31Z
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
publishDate: '2021-12-29T13:50:30.833598Z'
publication_types:
- '3'
abstract: 'Efficient video action recognition remains a challenging problem. One large model after another takes the place of the state-of-the-art on the Kinetics dataset, but real-world efficiency evaluations are often lacking. In this work, we fill this gap and investigate the use of transformers for efficient action recognition. We propose a novel, lightweight action recognition architecture, VideoLightFormer. In a factorized fashion, we carefully extend the 2D convolutional Temporal Segment Network with transformers, while maintaining spatial and temporal video structure throughout the entire model. Existing methods often resort to one of the two extremes, where they either apply huge transformers to video features, or minimal transformers on highly pooled video features. Our method differs from them by keeping the transformer models small, but leveraging full spatiotemporal feature structure. We evaluate VideoLightFormer in a high-efficiency setting on the temporally-demanding EPIC-KITCHENS-100 and Something-Something-V2 (SSV2) datasets and find that it achieves a better mix of efficiency and accuracy than existing state-of-the-art models, apart from the Temporal Shift Module on SSV2.'
publication: '*arXiv preprint arXiv:2107.00451*'
links:
- name: Link
  url: https://arxiv.org/abs/2107.00451
---
