---
title: " Optimal Time Complexity Algorithms for Computing General Random Walk Graph
  Kernels on Sparse Graphs "
software: " https://github.com/arijitthegame/efficient_random_walk_kernel "
openreview: " https://openreview.net/forum?id=NF1WK6BTRZ "
abstract: " We present the first linear time complexity randomized algorithms for
  unbiased approximation of the celebrated family of general random walk kernels (RWKs)
  for sparse graphs. This includes both labelled and unlabelled instances. The previous
  fastest methods for general RWKs were of cubic time complexity and not applicable
  to labelled graphs. Our method samples dependent random walks to compute novel graph
  embeddings in $R^{d}$ whose dot product is equal to the true RWK in expectation.
  It does so without instantiating the direct product graph in memory, meaning we
  can scale to massive datasets that cannot be stored on a single machine. We derive
  exponential concentration bounds to prove that our estimator is sharp, and show
  that the ability to approximate general RWKs (rather than just special cases) unlocks
  efficient implicit graph kernel learning. Our method is up to \\textbf{27$\\times$}
  faster than its counterparts for efficient computation on large graphs and scales
  to graphs \\textbf{128$\\times$} bigger than largest examples amenable to brute-force
  computation. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: choromanski25a
month: 0
tex_title: " Optimal Time Complexity Algorithms for Computing General Random Walk
  Graph Kernels on Sparse Graphs "
firstpage: 3457
lastpage: 3465
page: 3457-3465
order: 3457
cycles: false
bibtex_author: Choromanski, Krzysztof Marcin and Reid, Isaac and Sehanobish, Arijit
  and Dubey, Kumar Avinava
author:
- given: Krzysztof Marcin
  family: Choromanski
- given: Isaac
  family: Reid
- given: Arijit
  family: Sehanobish
- given: Kumar Avinava
  family: Dubey
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
pdf: https://raw.githubusercontent.com/mlresearch/v258/main/assets/choromanski25a/choromanski25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
