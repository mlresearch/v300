---
title: " Process-Tensor Tomography of SGD: Measuring Non-Markovian Memory via Back-Flow
  of Distinguishability "
openreview: TonOzlbE3k
abstract: " We model neural training as a classical multi-time map from controllable
  interventions—batch choices, augmentations, and optimizer micro-steps—to model predictions
  on a fixed probe set. On this basis, we introduce a simple, model-agnostic witness
  of training memory based on back-flow of distinguishability. In a controlled two-step
  protocol, we compare predictive distributions after one intervention versus two;
  a positive increase $\\Delta_{\\mathrm{BF}} = D_2 - D_1 > 0$, with $D\\in{\\mathrm{TV},
  \\mathrm{JS}, \\mathrm{H}}$, certifies observable-level non-Markovianity. Across
  controlled SGD experiments, we observe consistent positive back-flow with tight
  bootstrap confidence intervals, stronger effects under higher momentum, larger batch
  overlap, and more micro-steps, and marked collapse under a \\emph{causal break}
  that resets optimizer state. The witness is inexpensive, requires no architectural
  changes, and is robust across TV/JS/Hellinger. We position this as a measurement
  contribution: a practical diagnostic, and empirical evidence, that real training
  often deviates from the Markov idealization in ways that matter for optimizer behavior,
  data order, and schedule design. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: sevetlidis26a
month: 0
tex_title: " Process-Tensor Tomography of SGD: Measuring Non-Markovian Memory via
  Back-Flow of Distinguishability "
firstpage: 2521
lastpage: 2529
page: 2521-2529
order: 2521
cycles: false
bibtex_author: Sevetlidis, Vasileios and Pavlidis, George
author:
- given: Vasileios
  family: Sevetlidis
- given: George
  family: Pavlidis
date: 2026-08-30
address:
container-title: Proceedings of The 29th International Conference on Artificial Intelligence
  and Statistics
volume: '300'
genre: inproceedings
issued:
  date-parts:
  - 2026
  - 8
  - 30
pdf: https://raw.githubusercontent.com/mlresearch/v300/main/assets/sevetlidis26a/sevetlidis26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
