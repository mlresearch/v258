---
title: " Decision from Suboptimal Classifiers: Excess Risk Pre- and Post-Calibration "
software: " https://github.com/aperezlebel/decision_suboptimal_classifiers "
openreview: " https://openreview.net/forum?id=euoG9AE8qF "
abstract: " Probabilistic classifiers are central for making informed decisions under
  uncertainty. Based on the maximum expected utility principle, optimal decision rules
  can be derived using the posterior class probabilities and misclassification costs.
  Yet, in practice only learned approximations of the oracle posterior probabilities
  are available. In this work, we quantify the excess risk (a.k.a. regret) incurred
  using approximate posterior probabilities in batch binary decision-making. We provide
  analytical expressions for miscalibration-induced regret ($R^{CL}$), as well as
  tight and informative upper and lower bounds on the regret of calibrated classifiers
  ($R^{GL}$). These expressions allow us to identify regimes where recalibration alone
  addresses most of the regret, and regimes where the regret is dominated by the grouping
  loss, which calls for post-training beyond recalibration. Crucially, both $R^{CL}$
  and $R^{Gl}$ can be estimated in practice using a calibration curve and a recent
  grouping loss estimator. On NLP experiments, we show that these quantities identify
  when the expected gain of more advanced post-training is worth the operational cost.
  Finally, we highlight the potential of multicalibration approaches as efficient
  alternatives to costlier fine-tuning approaches. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: perez-lebel25a
month: 0
tex_title: " Decision from Suboptimal Classifiers: Excess Risk Pre- and Post-Calibration "
firstpage: 2395
lastpage: 2403
page: 2395-2403
order: 2395
cycles: false
bibtex_author: Perez-Lebel, Alexandre and Varoquaux, Gael and Koyejo, Sanmi and Doutreligne,
  Matthieu and Morvan, Marine Le
author:
- given: Alexandre
  family: Perez-Lebel
- given: Gael
  family: Varoquaux
- given: Sanmi
  family: Koyejo
- given: Matthieu
  family: Doutreligne
- given: Marine Le
  family: Morvan
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
pdf: https://raw.githubusercontent.com/mlresearch/v258/main/assets/perez-lebel25a/perez-lebel25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
