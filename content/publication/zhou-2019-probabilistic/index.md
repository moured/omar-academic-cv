---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Probabilistic rank-one tensor analysis with concurrent regularizations
subtitle: ''
summary: ''
authors:
- Yang Zhou
- Haiping Lu
- Yiu-Ming Cheung
tags: []
categories: []
date: '2021-07-01'
lastmod: 2021-12-29T13:50:15Z
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
publishDate: '2021-12-29T13:50:15.185026Z'
publication_types:
- '2'
abstract: 'Subspace learning for tensors attracts increasing interest in recent years, leading to the development of multilinear extensions of principal component analysis (PCA) and probabilistic PCA (PPCA). Existing multilinear PPCAs are based on the Tucker or CANDECOMP/PARAFAC (CP) models. Although both kinds of multilinear PPCAs have shown their effectiveness in dealing with tensors, they also have their own limitations. Tucker-based multilinear PPCAs have a restrictive subspace representation and suffer from rotational ambiguity, while CP-based ones are more prone to overfitting. To address these problems, we propose probabilistic rank-one tensor analysis (PROTA), a CP-based multilinear PPCA. PROTA has a more flexible subspace representation than Tucker-based PPCAs, and avoids rotational ambiguity. To alleviate overfitting for CP-based PPCAs, we propose two simple and effective regularization strategies, named as concurrent regularizations (CRs). By adjusting the noise variance or the moments of latent features, our strategies concurrently and coherently penalize the entire subspace. This relaxes unnecessary scale restrictions and gains more flexibility in regularizing CP-based PPCAs. To take full advantage of the probabilistic framework, we further propose a Bayesian treatment of PROTA, which achieves both automatic feature determination and robustness against overfitting. Experiments on synthetic and real-world datasets demonstrate the superiority of PROTA in subspace estimation and classification, as well as the effectiveness of CRs in alleviating overfitting.'
publication: '*IEEE Transactions on Cybernetics*'
links:
- name: Link
  url: https://doi.org/10.1109/TCYB.2019.2914316
---
