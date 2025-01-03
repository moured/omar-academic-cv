---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: A GNN-based multi-task learning framework for personalized video search
subtitle: ''
summary: ''
authors:
- Li Zhang
- Lei Shi
- Jiashu Zhao
- Juan Yang
- Tianshu Lyu
- Dawei Yin
- Haiping Lu
tags: []
categories: []
date: '2022-02-01'
lastmod: 2021-12-29T13:49:19Z
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
publishDate: '2021-12-29T13:49:17.680056Z'
publication_types:
- '1'
abstract: 'Watching online videos has become more and more popular and users tend to watch videos based on their personal tastes and preferences. Providing a customized ranking list to maximize the user’s satisfaction has become increasingly important for online video platforms. Existing personalized search methods (PSMs) train their models with user feedback information (e.g. clicks). However, we identified that such feedback signals may indicate attractiveness but not necessarily indicate relevance in video search. Besides, the click data and user historical information are usually too sparse to train a good PSM, which is different from the conventional Web search containing users’ rich historical information. To address these concerns, in this paper we propose a multi-task graph neural network architecture for personalized video search (MGNN-PVS) that can jointly model user’s click behaviour and the relevance between queries and videos. To relieve the sparsity problem and learn better representation for users, queries and videos, we develop an efficient and novel GNN architecture based on neighborhood sampling and hierarchical aggregation strategy by leveraging their different hops of neighbors in the user-query and query-document click graph. Extensive experiments on a major commercial video search engine show that our model significantly outperforms stateof-the-art PSMs, which illustrates the effectiveness of our proposed framework.'
publication: '*International Conference on Web Search and Data Mining (WSDM)*'
links:
- name: PDF
  url: http://staffwww.dcs.shef.ac.uk/people/H.Lu/Publications/GNNVideoSearch_WSDM2022.pdf
---
