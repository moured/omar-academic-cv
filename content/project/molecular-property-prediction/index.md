---
title: Molecular property prediction via line graph transformer
summary: Predict molecular properties with geometry-aware line graph transformer pre-training

tags:
- Multimodal AI
- AI4Science
- Selected
date: "2023-09-01"

authors:
- Peizhen Bai
- Xianyuan Liu
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
# url_code: ""
url_pdf: "https://arxiv.org/abs/2309.00483"
# url_slides: ""
url_video: "https://www.youtube.com/embed/ieiN7-vFPDE?start=1689&end=1982"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

Molecular property prediction with deep learning has gained much attention over the past years. Owing to the scarcity of labeled molecules, there has been growing interest in self-supervised learning methods that learn generalizable molecular representations from unlabeled data. Molecules are typically treated as 2D topological graphs in modeling, but it has been discovered that their 3D geometry is of great importance in determining molecular functionalities. In this paper, we propose the Geometry-aware line graph transformer (Galformer) pre-training, a novel self-supervised learning framework that aims to enhance molecular representation learning with 2D and 3D modalities. Specifically, we first design a dual-modality line graph transformer backbone to encode the topological and geometric information of a molecule. The designed backbone incorporates effective structural encodings to capture graph structures from both modalities. Then we devise two complementary pre-training tasks at the inter and intra-modality levels. These tasks provide properly supervised information and extract discriminative 2D and 3D knowledge from unlabeled molecules. Finally, we evaluate Galformer against six state-of-the-art baselines on twelve property prediction benchmarks via downstream fine-tuning. Experimental results show that Galformer consistently outperforms all baselines on both classification and regression tasks, demonstrating its effectiveness.

