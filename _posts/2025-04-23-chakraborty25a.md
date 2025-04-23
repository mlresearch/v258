---
title: Improving Pre-trained Self-Supervised Embeddings Through Effective Entropy
  Maximization
software: https://github.com/deepc94/e2mc
openreview: 4yQg5rixo0
abstract: A number of different architectures and loss functions have been applied
  to the problem of self-supervised learning (SSL), with the goal of developing embeddings
  that provide the best possible pre-training for as-yet-unknown, lightly supervised
  downstream tasks. One of these SSL criteria is to maximize the entropy of a set
  of embeddings in some compact space. But the goal of maximizing the embedding entropy
  often depends—whether explicitly or implicitly—upon high dimensional entropy estimates,
  which typically perform poorly in more than a few dimensions. In this paper, we
  motivate an effective entropy maximization criterion (E2MC), defined in terms of
  easy-to-estimate, low-dimensional constraints. We demonstrate that using it to continue
  training an already-trained SSL model for only a handful of epochs leads to a consistent
  and, in some cases, significant improvement in downstream performance. We perform
  careful ablation studies to show that the improved performance is due to the proposed
  add-on criterion. We also show that continued pre-training with alternative criteria
  does not lead to notable improvements, and in some cases, even degrades performance.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chakraborty25a
month: 0
tex_title: Improving Pre-trained Self-Supervised Embeddings Through Effective Entropy
  Maximization
firstpage: 433
lastpage: 441
page: 433-441
order: 433
cycles: false
bibtex_author: Chakraborty, Deep and LeCun, Yann and Rudner, Tim G. J. and Learned-Miller,
  Erik
author:
- given: Deep
  family: Chakraborty
- given: Yann
  family: LeCun
- given: Tim G. J.
  family: Rudner
- given: Erik
  family: Learned-Miller
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
pdf: https://raw.githubusercontent.com/mlresearch/v258/main/assets/chakraborty25a/chakraborty25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
