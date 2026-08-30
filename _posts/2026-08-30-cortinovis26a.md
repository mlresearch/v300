---
title: " Inverse-Free Sparse Variational Gaussian Processes "
openreview: zQZ6CSVoQj
abstract: " Gaussian processes (GPs) offer appealing properties but are costly to
  train at scale. Sparse variational GP (SVGP) approximations reduce cost yet still
  rely on Cholesky decompositions of kernel matrices, ill-suited to low-precision,
  massively parallel hardware. While one can construct valid variational bounds that
  rely only on matrix multiplications (matmuls) via an auxiliary matrix parameter,
  optimising them with off-the-shelf first-order methods is challenging. We make the
  inverse-free approach practical by proposing a better-conditioned bound and deriving
  a matmul-only natural-gradient update for the auxiliary parameter, markedly improving
  stability and convergence. We further provide simple heuristics, such as step-size
  schedules and stopping criteria, that make the overall optimisation routine fit
  seamlessly into existing workflows. Across regression and classification benchmarks,
  we demonstrate that our method 1) serves as a drop-in replacement in SVGP-based
  models (e.g., deep GPs), 2) recovers similar performance to traditional methods,
  and 3) can be faster than baselines when well tuned. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: cortinovis26a
month: 0
tex_title: " Inverse-Free Sparse Variational Gaussian Processes "
firstpage: 4195
lastpage: 4203
page: 4195-4203
order: 4195
cycles: false
bibtex_author: Cortinovis, Stefano and Aitchison, Laurence and Eleftheriadis, Stefanos
  and van der Wilk, Mark
author:
- given: Stefano
  family: Cortinovis
- given: Laurence
  family: Aitchison
- given: Stefanos
  family: Eleftheriadis
- given: Mark
  family: Wilk
  prefix: van der
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
pdf: https://raw.githubusercontent.com/mlresearch/v300/main/assets/cortinovis26a/cortinovis26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
