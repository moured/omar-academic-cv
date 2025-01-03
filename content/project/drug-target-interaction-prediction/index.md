---
title: Drug–target interaction prediction via bilinear attention network
summary: Advance drug discovery with interpretable bilinear attention network and domain adaptation 
tags:
- Multimodal AI
- AI4Health
- AI4Science
- Selected
date: "2023-02-01"

authors:
- Peizhen Bai
- Filip Miljkovic
- Bino John
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
url_code: "https://github.com/peizhenbai/DrugBAN"
url_pdf: "https://eprints.whiterose.ac.uk/195230/1/DrugBAN_NatMachIntell_2022.pdf"
# url_slides: ""
url_video: "https://www.youtube.com/embed/ieiN7-vFPDE?start=1992&end=2350"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Predicting drug–target interaction is key for drug discovery. Recent deep learning-based methods show promising performance, but two challenges remain: how to explicitly model and learn local interactions between drugs and targets for better prediction and interpretation and how to optimize generalization performance of predictions on novel drug–target pairs. Here, we present **DrugBAN**, a deep **B**ilinear **A**ttention **N**etwork (**BAN**) framework with domain adaptation to explicitly learn pairwise local interactions between drugs and targets, and adapt in response to out-of-distribution data. DrugBAN works on drug molecular graphs and target protein sequences to perform prediction, with conditional domain adversarial learning to align learned interaction representations across different distributions for better generalization on novel drug–target pairs. Experiments on three benchmark datasets under both in-domain and cross-domain settings show that DrugBAN achieves the best overall performance against five state-of-the-art baseline models. Moreover, visualizing the learned bilinear attention map provides interpretable insights from prediction results.
