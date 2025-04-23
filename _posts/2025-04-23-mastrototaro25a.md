---
title: Recursive Learning of Asymptotic Variational Objectives
software: https://github.com/matmulKTH/OSIWAE
openreview: O65WHcy4FR
abstract: General state-space models (SSMs) are widely used in statistical machine
  learning and are among the most classical generative models for sequential time-series
  data. SSMs, comprising latent Markovian states, can be subjected to variational
  inference (VI), but standard VI methods like the importance-weighted autoencoder
  (IWAE) lack functionality for streaming data. To enable online VI in SSMs when the
  observations are received in real time, we propose maximising an IWAE-type variational
  lower bound on the asymptotic contrast function, rather than the standard IWAE ELBO,
  using stochastic approximation. Unlike the recursive maximum likelihood method,
  which directly maximises the asymptotic contrast, our approach, called online sequential
  IWAE (OSIWAE), allows for online learning of both model parameters and a Markovian
  recognition model for inferring latent states. By approximating filter state posteriors
  and their derivatives using sequential Monte Carlo (SMC) methods, we create a particle-based
  framework for online VI in SSMs. This approach is more theoretically well-founded
  than recently proposed online variational SMC methods. We provide rigorous theoretical
  results on the learning objective and a numerical study demonstrating the method’s
  efficiency in learning model parameters and particle proposal kernels.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: mastrototaro25a
month: 0
tex_title: Recursive Learning of Asymptotic Variational Objectives
firstpage: 1432
lastpage: 1440
page: 1432-1440
order: 1432
cycles: false
bibtex_author: Mastrototaro, Alessandro and M{\"u}ller, Mathias and Olsson, Jimmy
author:
- given: Alessandro
  family: Mastrototaro
- given: Mathias
  family: Müller
- given: Jimmy
  family: Olsson
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
pdf: https://raw.githubusercontent.com/mlresearch/v258/main/assets/mastrototaro25a/mastrototaro25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
