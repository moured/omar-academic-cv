---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Neuropsychiatric disease classification using functional connectomics - results of the connectomics in neuroimaging transfer learning challenge
subtitle: ''
summary: ''
authors:
- Markus D. Schirmer
- Archana Venkataraman
- Islem Rekik
- Minjeong Kim
- Stewart H. Mostofsky
- Mary Beth Nebel
- Keri S. Rosch
- Karen E Seymour
- Deana Crocetti
- Hassna Irzan
- Michael Hütel
- Sébastien Ourselin
- Neil Marlow
- Andrew Melbourne
- Egor Levchenko
- Shuo Zhou
- Mwiza Kunda
- Haiping Lu
- Nicha C. Dvornek
- Juntang Zhuang
- Gideon Pinto
- Sandip Samal
- Jorge L. Bernal-Rusiel
- Rudolph Pienaar
- Ai Wern Chung
tags: []
categories: []
date: '2021-05-01'
lastmod: 2021-12-29T13:50:21Z
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
publishDate: '2021-12-29T13:50:20.453064Z'
publication_types:
- '2'
abstract: 'Large, open-source datasets, such as the Human Connectome Project and the Autism Brain Imaging Data Exchange, have spurred the development of new and increasingly powerful machine learning approaches for brain connectomics. However, one key question remains: are we capturing biologically relevant and generalizable information about the brain, or are we simply overfitting to the data? To answer this, we organized a scientific challenge, the Connectomics in NeuroImaging Transfer Learning Challenge (CNI-TLC), held in conjunction with MICCAI 2019. CNI-TLC included two classification tasks: (1) diagnosis of Attention-Deficit/Hyperactivity Disorder (ADHD) within a pre-adolescent cohort; and (2) transference of the ADHD model to a related cohort of Autism Spectrum Disorder (ASD) patients with an ADHD comorbidity. In total, 240 resting-state fMRI (rsfMRI) time series averaged according to three standard parcellation atlases, along with clinical diagnosis, were released for training and validation (120 neurotypical controls and 120 ADHD). We also provided Challenge participants with demographic information of age, sex, IQ, and handedness. The second set of 100 subjects (50 neurotypical controls, 25 ADHD, and 25 ASD with ADHD comorbidity) was used for testing. Classification methodologies were submitted in a standardized format as containerized Docker images through ChRIS, an open-source image analysis platform. Utilizing an inclusive approach, we ranked the methods based on 16 metrics: accuracy, area under the curve, F1-score, false discovery rate, false negative rate, false omission rate, false positive rate, geometric mean, informedness, markedness, Matthew’s correlation coefficient, negative predictive value, optimized precision, precision, sensitivity, and specificity. The final rank was calculated using the rank product for each participant across all measures. Furthermore, we assessed the calibration curves of each methodology. Five participants submitted their method for evaluation, with one outperforming all other methods in both ADHD and ASD classification. However, further improvements are still needed to reach the clinical translation of functional connectomics. We have kept the CNI-TLC open as a publicly available resource for developing and validating new classification methodologies in the field of connectomics.'
publication: '*Medical Image Analysis*'
links:
- name: Link
  url: https://doi.org/10.1016/j.media.2021.101972
---
