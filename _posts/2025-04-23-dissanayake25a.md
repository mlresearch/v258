---
title: Quantifying Knowledge Distillation using Partial Information Decomposition
software: https://github.com/pasandissanayake/kd-rid
openreview: xzLgVKWmz6
abstract: 'Knowledge distillation deploys complex machine learning models in resource-constrained
  environments by training a smaller student model to emulate internal representations
  of a complex teacher model. However, the teacher’s representations can also encode
  nuisance or additional information not relevant to the downstream task. Distilling
  such irrelevant information can actually impede the performance of a capacity-limited
  student model. This observation motivates our primary question: What are the information-theoretic
  limits of knowledge distillation? To this end, we leverage Partial Information Decomposition
  to quantify and explain the transferred knowledge and knowledge left to distill
  for a downstream task. We theoretically demonstrate that the task-relevant transferred
  knowledge is succinctly captured by the measure of redundant information about the
  task between the teacher and student. We propose a novel multi-level optimization
  to incorporate redundant information as a regularizer, leading to our framework
  of Redundant Information Distillation (RID). RID leads to more resilient and effective
  distillation under nuisance teachers as it succinctly quantifies task-relevant knowledge
  rather than simply aligning student and teacher representations.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: dissanayake25a
month: 0
tex_title: Quantifying Knowledge Distillation using Partial Information Decomposition
firstpage: 4474
lastpage: 4482
page: 4474-4482
order: 4474
cycles: false
bibtex_author: Dissanayake, Pasan and Hamman, Faisal and Halder, Barproda and Sucholutsky,
  Ilia and Zhang, Qiuyi and Dutta, Sanghamitra
author:
- given: Pasan
  family: Dissanayake
- given: Faisal
  family: Hamman
- given: Barproda
  family: Halder
- given: Ilia
  family: Sucholutsky
- given: Qiuyi
  family: Zhang
- given: Sanghamitra
  family: Dutta
date: 2025-04-23
address:
container-title: Proceedings of The 28th International Conference on Artificial Intelligence
  and Statistics
volume: '258'
genre: inproceedings
issued:
  date-parts:
  - 2025
  - 4
  - 23
pdf: https://raw.githubusercontent.com/mlresearch/v258/main/assets/dissanayake25a/dissanayake25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
