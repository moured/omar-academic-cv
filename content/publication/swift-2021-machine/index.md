---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: A machine learning cardiac magnetic resonance approach to extract disease features
  and automate pulmonary arterial hypertension diagnosis
subtitle: ''
summary: ''
authors:
- Andrew Swift
- Haiping Lu
- Johanna Uthoff
- Pankaj Garg
- Marcella Cogliano
- Jonathan Taylor
- Peter Metherall
- Shuo Zhou
- Christopher S Johns
- Samer Alabed
- Robin Condliffe
- Allan Lawrie
- Jim Wild
- David Kiely
tags: []
categories: []
date: '2021-02-01'
lastmod: 2021-12-29T13:50:19Z
featured: true
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
publishDate: '2021-12-29T13:50:17.949363Z'
publication_types:
- '2'
abstract: 'Aims: Pulmonary arterial hypertension (PAH) is a progressive condition with high mortality. Quantitative cardiovascular magnetic resonance (CMR) imaging metrics in PAH target individual cardiac structures and have diagnostic and prognostic utility but are challenging to acquire. The primary aim of this study was to develop and test a tensor-based machine learning approach to holistically identify diagnostic features in PAH using CMR, and secondarily, visualize and interpret key discriminative features associated with PAH.
<br><br>
Methods and results: Consecutive treatment naive patients with PAH or no evidence of pulmonary hypertension (PH), undergoing CMR and right heart catheterization within 48 h, were identified from the ASPIRE registry. A tensor-based machine learning approach, multilinear subspace learning, was developed and the diagnostic accuracy of this approach was compared with standard CMR measurements. Two hundred and twenty patients were identified: 150 with PAH and 70 with no PH. The diagnostic accuracy of the approach was high as assessed by area under the curve at receiver operating characteristic analysis (P < 0.001): 0.92 for PAH, slightly higher than standard CMR metrics. Moreover, establishing the diagnosis using the approach was less time-consuming, being achieved within 10 s. Learnt features were visualized in feature maps with correspondence to cardiac phases, confirming known and also identifying potentially new diagnostic features in PAH.
<br><br>
Conclusion: A tensor-based machine learning approach has been developed and applied to CMR. High diagnostic accuracy has been shown for PAH diagnosis and new learnt features were visualized with diagnostic potential.'
publication: '*European Heart Journal-Cardiovascular Imaging*'
links:
- name: Link
  url: https://doi.org/10.1093/ehjci/jeaa001
- name: PDF
  url: https://academic.oup.com/ehjcimaging/article-pdf/22/2/236/35973681/jeaa001.pdf
- name: Code
  url: https://github.com/pykale/pykale/tree/main/examples/cmri_mpca
- name: Data
  url: https://github.com/pykale/data/tree/main/images/ShefPAH-179  
- name: Colab demo
  url: https://colab.research.google.com/github/pykale/pykale/blob/main/examples/cmri_mpca/tutorial.ipynb  
---
