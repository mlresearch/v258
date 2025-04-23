---
title: Is Prior-Free Black-Box Non-Stationary Reinforcement Learning Feasible?
software: https://github.com/Grimoid/Is-BB-NS-RL-Feasible
openreview: OqOf8mtvVW
abstract: We study the problem of Non-Stationary Reinforcement Learning (NS-RL) without
  prior knowledge about the system’s non-stationarity. A state-of-the-art, black-box
  algorithm, known as MASTER, is considered, with a focus on identifying the conditions
  under which it can achieve its stated goals. Specifically, we prove that MASTER’s
  non-stationarity detection mechanism is not triggered for practical choices of horizon,
  leading to performance akin to a random restarting algorithm. Moreover, we show
  that the regret bound for MASTER, while being order optimal, stays above the worst-case
  linear regret until unreasonably large values of the horizon. To validate these
  observations, MASTER is tested for the special case of piecewise stationary multi-armed
  bandits, along with methods that employ random restarting, and others that use quickest
  change detection to restart. A simple, order optimal random restarting algorithm,
  that has prior knowledge of the non-stationarity is proposed as a baseline. The
  behavior of the MASTER algorithm is validated in simulations, and it is shown that
  methods employing quickest change detection are more robust and consistently outperform
  MASTER and other random restarting approaches.
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: gerogiannis25a
month: 0
tex_title: Is Prior-Free Black-Box Non-Stationary Reinforcement Learning Feasible?
firstpage: 2692
lastpage: 2700
page: 2692-2700
order: 2692
cycles: false
bibtex_author: Gerogiannis, Argyrios and Huang, Yu-Han and Veeravalli, Venugopal
author:
- given: Argyrios
  family: Gerogiannis
- given: Yu-Han
  family: Huang
- given: Venugopal
  family: Veeravalli
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
pdf: https://raw.githubusercontent.com/mlresearch/v258/main/assets/gerogiannis25a/gerogiannis25a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
