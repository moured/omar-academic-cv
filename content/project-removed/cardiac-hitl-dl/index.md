---
title: Human-in-the-loop DL for cardiac CT/MRI
summary: Interactively trained 'human-in-the-loop' deep learning to improve cardiac CT/MRI assessment for accurate therapy response and mortality prediction
tags:
- Deep Learning
- Medical Imaging
date: "2021-10-01"

authors:
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
# url_code: ""
# url_pdf: ""
# url_slides: ""
# url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

This project is an [NIHR AI in Health and Care Award](https://fundingawards.nihr.ac.uk/award/AI_AWARD01706).

Cardiovascular and pulmonary diseases account for close to half of all deaths in the UK. Diagnosing individuals with such conditions correctly and predicting whether they will respond to treatment is important to guide therapeutic intervention and achieve optimal outcomes. Cardiac magnetic resonance imaging (CMRI) and computed tomography (CT) scans are key to cardiac and pulmonary diagnosis. Current assessments are made by manual measurements (contours or landmarks) to derive meaningful information of heart function, or physiological parameters that are time-consuming and suffer from variability between individuals due to human error. Artificial intelligence using deep learning is pushing the limit of image analysis to an unprecedented level. Recently, a deep learning-based method trained on scans with high variability has been shown to achieve fully automated assessment of the left ventricle (LV) on CMRI. However, this level of automation has not been achieved for the right ventricle (RV) or the atrial chambers. RV failure is the key determinant of death in many cardiac conditions, but accurate RV assessment by human observers is challenging due to the more subtle anatomy and the thinner structures. There is a real clinical need to develop a fully automated assessment of the RV and all four cardiac chambers to derive meaningful physiological parameters.

The aim of this project is to develop an interactive human-in-the-loop multi-stage deep learning method to measure the health of the heart in large cohorts of patients with different cardiac and pulmonary conditions, scanned on different MRI/CT machines. This method will automatically generate physiological parameters and assess their ability to automatically predict treatment response and early death. In addition, we will assess the ability of machine learning to directly assess complex shape or/and motion of the heart to make a prognostic assessment from the automatic drawings on the heart.

Existing contour and landmark detection algorithms (known from our pilot assessments to be suboptimal) will be applied to scans of a large cohort of patients from different hospitals with diverse cardiac and pulmonary conditions. The measurements will be edited by a team of experienced consultants, these revised contours and landmarks will be fed back into the training to achieve an improved segmentation, and the process will repeat three times to achieve ideal accuracy. Feedback will be sought from doctors, imaging experts and patients.The deep learnt assessment of the heart will provide important measurements for predicting therapy response and survival in individuals with cardiac disease. The automatic physiological parameters and assessment of complex shape or/and motion produced by the deep learning approach could revolutionise disease assessment, and improve treatment delivery and patient care. Key advantages are rapid assessment, minimised human error and more consistent reporting of cardiac physiology and function.
