---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: 'APRILE: Exploring the molecular mechanisms of drug side effects with explainable
  graph neural networks'
subtitle: ''
summary: ''
authors:
- Hao Xu
- Shengqi Sang
- Herbert Yao
- Alexandra I Herghelegiu
- Haiping Lu
- Laurence Yang
tags: []
categories: []
date: '2021-07-01'
lastmod: 2021-12-29T13:50:33Z
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
publishDate: '2021-12-29T13:50:32.006143Z'
publication_types:
- '3'
abstract: 'With the majority of people 65 and over taking two or more medicines (polypharmacy), managing the side effects associated with polypharmacy is a global challenge. Explainable Artificial Intelligence (XAI) is necessary to reliably design safe polypharmacy. Here, we develop APRILE: a predictor-explainer framework based on graph neural networks to explore the molecular mechanisms underlying polypharmacy side effects by explaining predictions made by the predictors. For a side effect and its associated drug pair, or a set of side effects and their drug pairs, APRILE gives a set of proteins (drug targets or non-targets) and Gene Ontology (GO) items as the explanation. Using APRILE, we generate such explanations for 843,318 (learned) + 93,966 (novel) side effect–drug pair events, spanning 861 side effects (472 diseases, 485 symptoms and 9 mental disorders) and 20 disease categories. We show that our two new metrics, pharmacogenomic information utilization and protein-protein interaction information utilization, provide quantitative estimates of mechanism complexity. Explanations were significantly consistent with state of the art disease-gene associations for 232/239 (97%) side effects. Further, APRILE generated new insights into molecular mechanisms of four diverse categories of ADRs: infection, metabolic diseases, gastrointestinal diseases, and mental disorders, including paradoxical side effects. We demonstrate the viability of discovering polypharmacy side effect mechanisms by learning from an AI model trained on massive biomedical data. Consequently, it facilitates wider and more reliable use of AI in healthcare.'
publication: '*bioRxiv*'
links:
- name: Link
  url: https://doi.org/10.1101/2021.07.02.450937
- name: Code
  url: https://github.com/NYXFLOWER/APRILE
---
