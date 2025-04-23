---
title: Statistical Guarantees for Unpaired Image-to-Image Cross-Domain Analysis using
  GANs
software: https://github.com/saptarshic27/CG
openreview: lUu0cJ2ifh
abstract: "The field of unpaired image-to-image translation has undergone a significant
  transformation with the introduction of Generative Adversarial Networks (GANs),
  with CycleGAN and DiscoGAN as prominent variants.   While these models show impressive
  empirical performance, their statistical properties are  under-studied. In this
  paper, we propose a framework for analyzing the generalization error in cross-domain
  deep generative models. Our findings reveal that when provided with independent
  and identically distributed (i.i.d.) samples from two domains, the translation error,
  measured under the Wasserstein-1 loss, scales as $\\tilde{\\mathcal{O}} \\left(\\min(n,
  m)^{-1/\\max(d,\\tilde{d})}\\right)$, provided that the true model possesses sufficient
  smoothness and the network sizes are chosen appropriately. Here, $n$ and $m$ represent
  the sizes of the sample sets, while $d$ and $\\tilde{d}$ denote the dimensions of
  the respective data domains.  Furthermore, we highlight the importance of a cycle
  loss term for ensuring distributional cycle consistency.\tAdditionally, we provide
  insights into the relationship between the network size and the number of data points.
  Notably, as the true model exhibits greater smoothness, it suffices to work with
  smaller networks."
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chakraborty25b
month: 0
tex_title: Statistical Guarantees for Unpaired Image-to-Image Cross-Domain Analysis
  using GANs
firstpage: 2404
lastpage: 2412
page: 2404-2412
order: 2404
cycles: false
bibtex_author: Chakraborty, Saptarshi and Bartlett, Peter
author:
- given: Saptarshi
  family: Chakraborty
- given: Peter
  family: Bartlett
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
pdf: https://raw.githubusercontent.com/mlresearch/v258/main/assets/chakraborty25b/chakraborty25b.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
