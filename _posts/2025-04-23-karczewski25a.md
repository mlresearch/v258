---
title: " What Ails Generative Structure-based Drug Design: Expressivity is Too Little
  or Too Much? "
software: " https://github.com/rafalkarczewski/SimpleSBDD "
openreview: " https://openreview.net/forum?id=GHyBMTpiJg "
abstract: " Several generative models with elaborate training and sampling procedures
  have been proposed to accelerate structure-based drug design (SBDD); however, their
  empirical performance turns out to be suboptimal. We seek to better understand this
  phenomenon from both theoretical and empirical perspectives. Since most of these
  models apply graph neural networks (GNNs), one may suspect that they inherit the
  representational limitations of GNNs. We analyze this aspect, establishing the first
  such results for protein-ligand complexes. A plausible counterview may attribute
  the underperformance of these models to their excessive parameterizations, inducing
  expressivity at the expense of generalization. We investigate this possibility with
  a simple metric-aware approach that learns an economical surrogate for affinity
  to infer an unlabelled molecular graph and optimizes for labels conditioned on this
  graph and molecular properties. The resulting model achieves state-of-the-art results
  using 100x fewer trainable parameters and affords up to 1000x speedup. Collectively,
  our findings underscore the need to reassess and redirect the existing paradigm
  and efforts for SBDD. Code is available at \\url{https://github.com/rafalkarczewski/SimpleSBDD.} "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: karczewski25a
month: 0
tex_title: " What Ails Generative Structure-based Drug Design: Expressivity is Too
  Little or Too Much? "
firstpage: 3187
lastpage: 3195
page: 3187-3195
order: 3187
cycles: false
bibtex_author: Karczewski, Rafal and Kaski, Samuel and Heinonen, Markus and Garg,
  Vikas K
author:
- given: Rafal
  family: Karczewski
- given: Samuel
  family: Kaski
- given: Markus
  family: Heinonen
- given: Vikas K
  family: Garg
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
pdf: https://raw.githubusercontent.com/mlresearch/v258/main/assets/karczewski25a/karczewski25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
