---
title: " A Projection-Based Framework for Gradient-Free and Parallel Learning "
openreview: 2OaL8xOlh3
abstract: " We present a feasibility-seeking approach to neural network training.
  This mathematical optimization framework is distinct from conventional gradient-based
  loss minimization and uses projection operators and iterative projection algorithms.
  We reformulate training as a large-scale feasibility problem: finding network parameters
  and states that satisfy local constraints derived from its elementary operations.
  Training then involves projecting onto these constraints, a local operation that
  can be parallelized across the network. We introduce PJAX, a JAX-based software
  framework that enables this paradigm. PJAX composes projection operators for elementary
  operations, automatically deriving the solution operators for the feasibility problems
  (akin to autodiff for derivatives). It inherently supports GPU/TPU acceleration,
  provides a familiar NumPy-like API, and is extensible. We train diverse architectures
  (MLPs, CNNs, RNNs) on standard benchmarks using PJAX, demonstrating its functionality
  and generality. Our results show that this approach is a compelling alternative
  to gradient-based training, with clear advantages in parallelism and the ability
  to handle non-differentiable operations. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: bergmeister26a
month: 0
tex_title: " A Projection-Based Framework for Gradient-Free and Parallel Learning "
firstpage: 2746
lastpage: 2754
page: 2746-2754
order: 2746
cycles: false
bibtex_author: Bergmeister, Andreas and Lal, Manish Krishan and Jegelka, Stefanie
  and Sra, Suvrit
author:
- given: Andreas
  family: Bergmeister
- given: Manish Krishan
  family: Lal
- given: Stefanie
  family: Jegelka
- given: Suvrit
  family: Sra
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
pdf: https://raw.githubusercontent.com/mlresearch/v300/main/assets/bergmeister26a/bergmeister26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
