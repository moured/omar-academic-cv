---
title: Mixed-order spectral clustering for networks
summary: Model both second-order and third-order structures simultaneously for complex networks

tags:
- Graph Machine Learning
- Interpretable Machine Learning
date: "2021-09-01"

authors:
- Yan Ge
- Haiping Lu

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: 
  focal_point: Smart

# links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: "https://bitbucket.org/Yan_Sheffield/mosc/src/master/"
url_pdf: "https://eprints.whiterose.ac.uk/172646/1/MOSC_PR21.pdf"
# url_slides: ""
# url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Spectral clustering (SC) is a popular approach for gaining insights from complex networks. Conventional SC focuses on second-order structures (e.g. edges) without direct consideration of higher-order structures (e.g. triangles). This has motivated SC extensions that directly consider higher-order structures. However, both approaches are limited to considering a single order. 

To address this issue, we propose a novel Mixed-Order Spectral Clustering (MOSC) framework to model both second-order and third-order structures simultaneously. To model mixed-order structures, we propose two new methods based on Graph Laplacian (GL) and Random Walks (RW). MOSC-GL combines edge and triangle adjacency matrices, with theoretical performance guarantee. MOSC-RW combines first-order and second-order random walks for a probabilistic interpretation. Moreover, we design mixed-order cut criteria to enable existing SC methods to preserve mixed-order structures, and develop new mixed-order evaluation metrics for structure-level evaluation. Experiments on community detection and superpixel segmentation show (1) the superior performance of the MOSC methods over existing SC methods, (2) enhanced performance of conventional SC due to mixed-order cut criteria, and (3) new insights of output clusters offered by the mixed-order evaluation metrics.