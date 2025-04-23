---
title: Dissecting the Impact of Model Misspecification in Data-Driven Optimization
openreview: Q1deZl7rFQ
abstract: Data-driven optimization aims to translate a machine learning model into
  decision-making by optimizing decisions on estimated costs. Such a pipeline can
  be conducted by fitting a distributional model which is then plugged into the target
  optimization problem. While this fitting can utilize traditional methods such as
  maximum likelihood, a more recent approach uses estimation-optimization integration
  that minimizes decision error instead of estimation error. Although intuitive, the
  statistical benefit of the latter approach is not well understood yet is important
  to guide the prescriptive usage of machine learning. In this paper, we dissect the
  performance comparisons between these approaches in terms of the amount of model
  misspecification. In particular, we show how the integrated approach offers a “universal
  double benefit” on the top two dominating terms of regret when the underlying model
  is misspecified, while the traditional approach can be advantageous when the model
  is nearly well-specified. Our comparison is powered by finite-sample tail regret
  bounds that are derived via new higher-order expansions of regrets and the leveraging
  of a recent Berry-Esseen theorem.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: elmachtoub25a
month: 0
tex_title: Dissecting the Impact of Model Misspecification in Data-Driven Optimization
firstpage: 1594
lastpage: 1602
page: 1594-1602
order: 1594
cycles: false
bibtex_author: Elmachtoub, Adam N. and Lam, Henry and Lan, Haixiang and Zhang, Haofeng
author:
- given: Adam N.
  family: Elmachtoub
- given: Henry
  family: Lam
- given: Haixiang
  family: Lan
- given: Haofeng
  family: Zhang
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
pdf: https://raw.githubusercontent.com/mlresearch/v258/main/assets/elmachtoub25a/elmachtoub25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
