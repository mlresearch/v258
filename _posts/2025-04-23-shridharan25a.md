---
title: " $β$-th order Acyclicity Derivatives for DAG Learning "
software: " https://github.com/higherorderderivatives2024/Higher-Order-Acyclicity-Derivatives-for-DAG-Learning "
openreview: " https://openreview.net/forum?id=UOLZv2azUe "
abstract: " We consider a non-convex optimization  formulation for learning the weighted
  adjacency matrix $W$ of a directed acyclic graph (DAG) that uses acyclicity constraints
  that are functions of $|W_{ij}|^\\beta$, for $\\beta \\in \\mathbb{N}$. State-of-the-art
  algorithms for this problem use gradient-based Karush-Kuhn-Tucker (KKT) optimality
  conditions which only yield useful search directions for $\\beta =1$. Therefore,
  constraints with $\\beta \\geq 2$ have been ignored in the literature, and their
  empirical performance remains unknown. We introduce $\\beta$-th Order Taylor Series
  Expansion Based Local Search ($\\beta$-LS) which yields actionable descent directions
  for any $\\beta \\in \\mathbb{N}$. Our empirical experiments show that $2$-LS obtains
  solutions of  higher quality than $1$-LS, $3$-LS and $4$-LS. $2$-LSopt, an optimized
  version of $2$-LS, obtains high quality solutions significantly faster than the
  state of the art which uses $\\beta=1$. Moreover, $2$-LSopt does not need any graph-size
  specific hyperparameter tuning. We prove that $\\beta$-LSopt is guaranteed to converge
  to a Coordinate-Wise Local Stationary Point (Cst) for any $\\beta \\in \\mathbb{N}$.
  If the objective function is convex, $\\beta$-LSopt converges to a local minimum. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: shridharan25a
month: 0
tex_title: " $β$-th order Acyclicity Derivatives for DAG Learning "
firstpage: 208
lastpage: 216
page: 208-216
order: 208
cycles: false
bibtex_author: Shridharan, Madhumitha and Iyengar, Garud
author:
- given: Madhumitha
  family: Shridharan
- given: Garud
  family: Iyengar
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
pdf: https://raw.githubusercontent.com/mlresearch/v258/main/assets/shridharan25a/shridharan25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
