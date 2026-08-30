---
title: " Panprediction: Optimal Predictions for Any Downstream Task and Loss "
openreview: odEg4PE8jp
abstract: " Supervised learning is classically formulated as training a model to minimize
  a fixed loss function over a fixed distribution, or task. However, an emerging paradigm
  instead views model training as extracting enough information from data so that
  the model can be used to minimize many losses on many downstream tasks. We formalize
  a mathematical framework for this paradigm, which we call panprediction, and study
  its statistical complexity. Formally, panprediction generalizes omniprediction (Gopalan
  et al., 2021) and sits upstream from multi-group learning (Rothblum and Yona, 2021),
  which respectively focus on predictions that generalize to many downstream losses
  or many downstream tasks, but not both. Concretely, we design algorithms that learn
  deterministic and randomized panpredictors with $\\tilde{O}(1/\\varepsilon^3)$ and
  $\\tilde{O}(1/\\varepsilon^2)$ samples, respectively. Our results demonstrate that
  under mild assumptions, simultaneously minimizing infinitely many losses on infinitely
  many tasks can be as statistically easy as minimizing one loss on one task. Along
  the way, we improve the best known sample complexity guarantee of deterministic
  omniprediction by a factor of $1/\\varepsilon$, and match all other known sample
  complexity guarantees of omniprediction and multi-group learning. Our key technical
  ingredient is a nearly lossless reduction from panprediction to a statistically
  efficient notion of calibration, called step calibration. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: balakrishnan26a
month: 0
tex_title: " Panprediction: Optimal Predictions for Any Downstream Task and Loss "
firstpage: 4321
lastpage: 4329
page: 4321-4329
order: 4321
cycles: false
bibtex_author: Balakrishnan, Sivaraman and Haghtalab, Nika and Hsu, Daniel and Lee,
  Brian W and Zhao, Eric
author:
- given: Sivaraman
  family: Balakrishnan
- given: Nika
  family: Haghtalab
- given: Daniel
  family: Hsu
- given: Brian W
  family: Lee
- given: Eric
  family: Zhao
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
pdf: https://raw.githubusercontent.com/mlresearch/v300/main/assets/balakrishnan26a/balakrishnan26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
