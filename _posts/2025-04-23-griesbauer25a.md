---
title: " TVineSynth: A Truncated C-Vine Copula Generator of Synthetic Tabular Data
  to Balance Privacy and Utility "
software: " https://github.com/ElisabethGriesbauer/T-Vine-Synth "
openreview: " https://openreview.net/forum?id=tpxxNenfDT "
abstract: " We propose TVineSynth, a vine copula based synthetic tabular data generator,
  which is designed to balance privacy and utility, using the vine tree structure
  and its truncation to do the trade-off. Contrary to synthetic data generators that
  achieve DP by globally adding noise, TVineSynth performs a controlled approximation
  of the estimated data generating distribution, so that it does not suffer from poor
  utility of the resulting synthetic data for downstream prediction tasks. TVineSynth
  introduces a targeted bias into the vine copula model that, combined with the specific
  tree structure of the vine, causes the model to zero out privacy-leaking dependencies
  while relying on those that are beneficial for utility. Privacy is here measured
  with membership (MIA) and attribute inference attacks (AIA). Further, we theoretically
  justify how the construction of TVineSynth ensures AIA privacy under a natural privacy
  measure for continuous sensitive attributes. When compared to competitor models,
  with and without DP, on simulated and on real-world data, TVineSynth achieves a
  superior privacy-utility balance. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: griesbauer25a
month: 0
tex_title: " TVineSynth: A Truncated C-Vine Copula Generator of Synthetic Tabular
  Data to Balance Privacy and Utility "
firstpage: 3511
lastpage: 3519
page: 3511-3519
order: 3511
cycles: false
bibtex_author: Griesbauer, Elisabeth and Czado, Claudia and Frigessi, Arnoldo and
  Haff, Ingrid Hob{\ae}k
author:
- given: Elisabeth
  family: Griesbauer
- given: Claudia
  family: Czado
- given: Arnoldo
  family: Frigessi
- given: Ingrid Hobæk
  family: Haff
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
pdf: https://raw.githubusercontent.com/mlresearch/v258/main/assets/griesbauer25a/griesbauer25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
