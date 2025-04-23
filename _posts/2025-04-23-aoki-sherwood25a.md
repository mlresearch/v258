---
title: 'When the Universe is Too Big: Bounding Consideration Probabilities for Plackett-Luce
  Rankings'
software: https://github.com/aoki-sherwoodb/bounding-consideration-probs
openreview: l0gLH8H3Xe
abstract: The widely used Plackett-Luce ranking model assumes that individuals rank
  items by making repeated choices from a universe of items. But in many cases the
  universe is too big for people to plausibly consider all options. In the choice
  literature, this issue has been addressed by supposing that individuals first sample
  a small consideration set and then choose among the considered items. However, inferring
  unobserved consideration sets (or item consideration probabilities) in this “consider
  then choose” setting poses significant challenges, because even simple models of
  consideration with strong independence assumptions are not identifiable, even if
  item utilities are known. We apply the consider-then-choose framework to top-$k$
  rankings, where we assume rankings are constructed according to a Plackett-Luce
  model after sampling a consideration set. While item consideration probabilities
  remain non-identified in this setting, we prove that we can infer bounds on the
  relative values of consideration probabilities.  Additionally, given a condition
  on the expected consideration set size and known item utilities, we derive absolute
  upper and lower bounds on item consideration probabilities. We also provide algorithms
  to tighten those bounds on consideration probabilities by propagating inferred constraints.
  Thus, we show that we can learn useful information about consideration probabilities
  despite not being able to identify them precisely. We demonstrate our methods on
  a ranking dataset from a psychology experiment with two different ranking tasks
  (one with fixed consideration sets and one with unknown consideration sets). This
  combination of data allows us to estimate utilities and then learn about unknown
  consideration probabilities using our bounds.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: aoki-sherwood25a
month: 0
tex_title: 'When the Universe is Too Big: Bounding Consideration Probabilities for
  Plackett-Luce Rankings'
firstpage: 2368
lastpage: 2376
page: 2368-2376
order: 2368
cycles: false
bibtex_author: Aoki-Sherwood, Ben and Bregou, Catherine and Liben-Nowell, David and
  Tomlinson, Kiran and Zeng, Thomas
author:
- given: Ben
  family: Aoki-Sherwood
- given: Catherine
  family: Bregou
- given: David
  family: Liben-Nowell
- given: Kiran
  family: Tomlinson
- given: Thomas
  family: Zeng
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
pdf: https://raw.githubusercontent.com/mlresearch/v258/main/assets/aoki-sherwood25a/aoki-sherwood25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
