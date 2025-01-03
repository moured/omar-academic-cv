---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: Learning compact binary codes from higher-order tensors via free-form reshaping
  and binarized multilinear PCA
subtitle: ''
summary: ''
authors:
- Haiping Lu
- Jianxin Wu
- Yu Zhang
tags: []
categories: []
date: '2016-07-01'
lastmod: 2021-12-29T13:50:01Z
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
publishDate: '2021-12-29T13:50:00.060864Z'
publication_types:
- '1'
abstract: 'For big, high-dimensional dense features, it is important to learn compact binary codes or compress them for greater memory efficiency. This paper proposes a Binarized Multilinear PCA (BMP) method for this problem with Free-Form Reshaping (FFR) of such features to higher-order tensors, lifting the structure-modelling restriction in traditional tensor models. The reshaped tensors are transformed to a subspace using multilinear PCA. Then, we unsupervisedly select features and supervisedly binarize them with a minimum-classification-error scheme to get compact binary codes. We evaluate BMP on two scene recognition datasets against state-of-the-art algorithms. The FFR works well in experiments. With the same number of compression parameters (model size), BMP has much higher classification accuracy. To achieve the same accuracy or compression ratio, BMP has an order of magnitude smaller number of compression parameters. Thus, BMP has great potential in memory-sensitive applications such as mobile computing and big data analytics.'
publication: '*International Joint Conference on Neural Networks (IJCNN)*'
links:
- name: Link
  url: https://doi.org/10.1109/IJCNN.2016.7727581
---
