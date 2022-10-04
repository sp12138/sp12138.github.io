---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="https://scholar.google.com/citations?user=h_VczmEAAAAJ&hl=zh-CN&oi=ao">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
## Publications
$^\dagger$ indicates equal contributions,  $^\ast$indicates corresponding author.

- [<span style="color:blue"><strong>IJCAI’22</strong></span>]Federated Learning on Heterogeneous and Long-Tailed Data via Classifier Re-Training with Federated Features
  **Xinyi Shang**, Yang Lu$^\ast$, Gang Huang, and Hanzi Wang
  *International Joint Conference on Artificial Intelligence*, pp.2218-2224, Vienna, Austria, July 23-29, 2022. (CCF A) [[arXiv](https://arxiv.org/abs/2204.13399)][[code](https://github.com/shangxinyi/CReFF-FL)]
- [<span style="color:blue"><strong>ICME’22 (Oral)</strong></span>] FEDIC: Federated Learning on Non-IID and Long-Tailed Data via Calibrated Distillation
  **Xinyi Shang**, Yang Lu$^\ast$, Yiu-ming Cheung, and Hanzi Wang
  *IEEE International Conference on Multimedia and Expo*, pp.1-6, Taipei, Taiwan, July 18-22, 2022. (CCF B) [[arXiv](https://arxiv.org/abs/2205.00172)][[code](https://github.com/shangxinyi/FEDIC)]
- [<span style="color:blue"><strong>专利</strong></span>]卢杨,**尚心怡**, 黄刚, 华炜, 王菡子. 一种面向长尾异构数据的联邦学习方法. 专利申请公布号: CN114429219A, 申请日: 2021.12.09, 申请公布日: 2022.05.03.
- [<span style="color:blue"><strong>Preprint</strong></span>]Xinyi Shang$^\dagger$, Gang Huang$^\dagger$, Yang Lu$^\ast$, Jian Lou, Bo Han, Yiu-ming Cheung, and Hanzi Wang, ``Federated Semi-Supervised Learning with Annotation Heterogeneity'', 2022.

