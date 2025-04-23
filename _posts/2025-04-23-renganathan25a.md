---
title: "$q\\textttPOTS$: Efficient Batch Multiobjective Bayesian Optimization via
  Pareto Optimal Thompson Sampling"
software: https://github.com/csdlpsu/qpots
openreview: 5qYVbLA1lK
abstract: 'Classical evolutionary approaches for multiobjective optimization are quite
  accurate but incur a lot of queries to the objectives; this can be prohibitive when
  objectives are expensive oracles. A sample-efficient approach to solving multiobjective
  optimization is via Gaussian process (GP) surrogates and Bayesian optimization (BO).
  Multiobjective Bayesian optimization (MOBO) involves the construction of an acquisition
  function which is optimized to acquire new observation candidates sequentially.
  This “inner” optimization can be hard due to various reasons: acquisition functions
  being nonconvex, nondifferentiable and/or unavailable in analytical form; batch
  sampling usually exacerbates these problems and the success of MOBO heavily relies
  on this inner optimization. This, ultimately, affects their sample efficiency. To
  overcome these challenges, we propose a Thompson sampling (TS) based approach ($q\texttt{POTS}$).
  Whereas TS chooses candidates according to the probability that they are optimal,
  $q\texttt{POTS}$ chooses candidates according to the probability that they are Pareto
  optimal. Instead of a hard acquisition function optimization, $q\texttt{POTS}$ solves
  a cheap multiobjective optimization on the GP posteriors with evolutionary approaches.
  This way we get the best of both worlds: accuracy of evolutionary approaches and
  sample-efficiency of MOBO. New candidates are chosen on the posterior GP Pareto
  frontier according to a maximin distance criterion. $q\texttt{POTS}$ is endowed
  with theoretical guarantees, a natural exploration-exploitation trade-off, and superior
  empirical performance.'
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: renganathan25a
month: 0
tex_title: "$q\\texttt{POTS}$: Efficient Batch Multiobjective Bayesian Optimization
  via Pareto Optimal Thompson Sampling"
firstpage: 4051
lastpage: 4059
page: 4051-4059
order: 4051
cycles: false
bibtex_author: Renganathan, Ashwin and Carlson, Kade
author:
- given: Ashwin
  family: Renganathan
- given: Kade
  family: Carlson
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
pdf: https://raw.githubusercontent.com/mlresearch/v258/main/assets/renganathan25a/renganathan25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
