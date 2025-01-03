---
title: Multisite brain fMRI classification
summary: Classify autism across multiple sites via site-dependence minimisation & second-order functional connectivity
tags:
- Multimodal AI
- AI4Health
- Medical Imaging
- Interpretable Machine Learning
- Selected
date: "2021-06-02"

authors:
- Mwiza Kunda
- Shuo Zhou
- Gaolang Gong
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
url_code: "https://github.com/kundaMwiza/fMRI-site-adaptation"
url_pdf: "https://eprints.whiterose.ac.uk/191961/1/MultisiteASD_TMI_2022.pdf"
# url_slides: ""
url_video: "https://www.youtube.com/embed/6ctAjZi70tA?start=230&end=677"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Autism spectrum disorder (ASD) has no objective diagnosis method despite having a high prevalence. Machine learning has been widely used to develop classification models for ASD using neuroimaging data. Recently, studies have shifted towards using large multi-site neuroimaging datasets to boost the clinical applicability and statistical power of results. However, the classification performance is hindered by the heterogeneous nature of agglomerative datasets. 

In this project, we propose new methods for multi-site autism classification using the Autism Brain Imaging Data Exchange (ABIDE) dataset. We firstly propose a new second-order measure of functional connectivity (FC) named as Tangent Pearson embedding to extract better features for classification. Then we assess the statistical dependence between acquisition sites and FC features, and apply a domain adaptation approach to minimise the site dependence of FC features to improve classification. Our analysis shows that 1) statistical dependence between site and FC features is statistically significant at the 5% level, and 2) extracting second-order features from neuroimaging data and minimising their site dependence can improve over state-of-the-art classification results on the ABIDE dataset, achieving a classification accuracy of 73%.