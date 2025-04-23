---
title: " Differentiable Causal Structure Learning with Identifiability by NOTIME "
software: " https://github.com/STAN-UAntwerp/NOTIME "
openreview: " https://openreview.net/forum?id=C4oYj4q4rC "
abstract: " The introduction of the NOTEARS algorithm resulted in a wave of research
  on differentiable Directed Acyclic Graph (DAG) learning. Differentiable DAG learning
  transforms the combinatorial problem of identifying the DAG underlying a Structural
  Causal Model (SCM) into a constrained continuous optimization problem. Being differentiable,
  these problems can be solved using gradient-based tools which allow integration
  into other differentiable objectives. However, in contrast to classical constrained-based
  algorithms, the identifiability properties of differentiable algorithms are poorly
  understood. We illustrate that even in the well-known Linear Non-Gaussian Additive
  Model (LiNGAM), the current state-of-the-art methods do not identify the true underlying
  DAG. To address the issue, we propose NOTIME  (\\emph{Non-combinatorial Optimization
  of Trace exponential and Independence MEasures}), the first differentiable DAG learning
  algorithm with \\emph{provable} identifiability guarantees under the LiNGAM by building
  on a measure of (joint) independence. With its identifiability guarantees, NOTIME
  remains invariant to normalization of the data on a population level, a property
  lacking in existing methods. NOTIME compares favourably against NOTEARS and other
  (scale-invariant) differentiable DAG learners, across different noise distributions
  and normalization procedures. Introducing the first identifiability guarantees to
  general LiNGAM is an important step towards practical adoption of differentiable
  DAG learners. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: berrevoets25a
month: 0
tex_title: " Differentiable Causal Structure Learning with Identifiability by NOTIME "
firstpage: 3115
lastpage: 3123
page: 3115-3123
order: 3115
cycles: false
bibtex_author: Berrevoets, Jeroen and Raymaekers, Jakob and van der Schaar, Mihaela
  and Verdonck, Tim and Yao, Ruicong
author:
- given: Jeroen
  family: Berrevoets
- given: Jakob
  family: Raymaekers
- given: Mihaela
  family: Schaar
  prefix: van der
- given: Tim
  family: Verdonck
- given: Ruicong
  family: Yao
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
pdf: https://raw.githubusercontent.com/mlresearch/v258/main/assets/berrevoets25a/berrevoets25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
