---
title: " Unbiased and Sign Compression in Distributed Learning: Comparing Noise Resilience
  via SDEs "
openreview: " https://openreview.net/forum?id=RRrftHtEfK "
abstract: " Distributed methods are essential for handling machine learning pipelines
  comprising large-scale models and datasets. However, their benefits often come at
  the cost of increased communication overhead between the central server and agents,
  which can become the main bottleneck, making training costly or even unfeasible
  in such systems. Compression methods such as quantization and sparsification can
  alleviate this issue. Still, their robustness to large and heavy-tailed gradient
  noise, a phenomenon sometimes observed in language modeling, remains poorly understood.
  This work addresses this gap by analyzing Distributed Compressed SGD (DCSGD) and
  Distributed SignSGD (DSignSGD) using stochastic differential equations (SDEs). Our
  results show that DCSGD with unbiased compression is more vulnerable to noise in
  stochastic gradients, while DSignSGD remains robust, even under large and heavy-tailed
  noise. Additionally, we propose new scaling rules for hyperparameter tuning to mitigate
  performance degradation due to compression. These findings are empirically validated
  across multiple deep learning architectures and datasets, providing practical recommendations
  for distributed optimization. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: compagnoni25a
month: 0
tex_title: " Unbiased and Sign Compression in Distributed Learning: Comparing Noise
  Resilience via SDEs "
firstpage: 4087
lastpage: 4095
page: 4087-4095
order: 4087
cycles: false
bibtex_author: Compagnoni, Enea Monzio and Islamov, Rustem and Proske, Frank Norbert
  and Lucchi, Aurelien
author:
- given: Enea Monzio
  family: Compagnoni
- given: Rustem
  family: Islamov
- given: Frank Norbert
  family: Proske
- given: Aurelien
  family: Lucchi
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
pdf: https://raw.githubusercontent.com/mlresearch/v258/main/assets/compagnoni25a/compagnoni25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
