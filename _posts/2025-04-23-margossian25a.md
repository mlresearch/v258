---
title: 'Variational Inference in Location-Scale Families: Exact Recovery of the Mean
  and Correlation Matrix'
software: https://github.com/charlesm93/VI_location_robust
openreview: ZCWIEDEWZP
abstract: Given an intractable target density $p$, variational inference (VI) attempts
  to find the best approximation $q$ from a tractable family $\mathcal Q$. This is
  typically done by minimizing the exclusive Kullback-Leibler divergence, $\text{KL}(q||p)$.
  In practice, $\mathcal Q$ is not rich enough to contain $p$, and the approximation
  is misspecified even when it is a unique global minimizer of $\text{KL}(q||p)$.
  In this paper, we analyze the robustness of VI to these misspecifications when $p$
  exhibits certain symmetries and $\mathcal Q$ is a location-scale family that shares
  these symmetries. We prove strong guarantees for VI not only under mild regularity
  conditions but also in the face of severe misspecifications. Namely, we show that
  (i) VI recovers the mean of $p$ when $p$ exhibits an even symmetry, and (ii) it
  recovers the correlation matrix of $p$ when in addition $p$ exhibits an elliptical
  symmetry. These guarantees hold for the mean even when $q$ is factorized and $p$
  is not, and for the correlation matrix even when $q$ and $p$ behave differently
  in their tails. We analyze various regimes of Bayesian inference where these symmetries
  are useful idealizations, and we also investigate experimentally how VI behaves
  in their absence.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: margossian25a
month: 0
tex_title: 'Variational Inference in Location-Scale Families: Exact Recovery of the
  Mean and Correlation Matrix'
firstpage: 3466
lastpage: 3474
page: 3466-3474
order: 3466
cycles: false
bibtex_author: Margossian, Charles and Saul, Lawrence K.
author:
- given: Charles
  family: Margossian
- given: Lawrence K.
  family: Saul
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
pdf: https://raw.githubusercontent.com/mlresearch/v258/main/assets/margossian25a/margossian25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
