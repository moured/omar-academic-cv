---
title: Uncertainty estimation for landmark localisation
summary: Quantify the uncertainty in automatic anatomical landmark localisation
tags:
- AI4Health
- Medical Imaging
- Interpretable Machine Learning
# - Selected
date: "2022-11-16"

authors:
- Lawrence Schobs
- Andrew Swift
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
url_code: "https://github.com/schobs/qbin"
url_pdf: "https://eprints.whiterose.ac.uk/195227/1/Qbin_TMI_2022.pdf"
# url_slides: ""
# url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Automatic anatomical landmark localisation has made great strides by leveraging deep learning methods in recent years. The ability to quantify the uncertainty of these predictions is a vital ingredient needed to see these methods adopted in clinical use, where it is imperative that erroneous predictions are caught and corrected. 

We propose Quantile Binning, a data-driven method to categorise predictions by uncertainty with estimated error bounds. This framework can be applied to any continuous uncertainty measure, allowing straightforward identification of the best subset of predictions with accompanying estimated error bounds. We facilitate easy comparison between uncertainty measures by constructing two evaluation metrics derived from Quantile Binning. We demonstrate this framework by comparing and contrasting three uncertainty measures (a baseline, the current gold standard, and a proposed method combining aspects of the two), across two datasets (one easy, one hard) and two heatmap-based landmark localisation model paradigms (U-Net based and patch-based). We conclude by illustrating how filtering out gross mispredictions caught in our Quantile Bins significantly improves the proportion of predictions under an acceptable error threshold, and offer recommendations on which uncertainty measure to use and how to use it.  