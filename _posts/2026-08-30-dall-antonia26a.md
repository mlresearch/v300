---
title: " Boosted GFlowNets: Improving Exploration via Sequential Learning "
openreview: XbH8QaJ6Mh
abstract: " Generative Flow Networks (GFlowNets) are powerful samplers for compositional
  objects that, by design, sample proportionally to a given non-negative reward. Nonetheless,
  in practice, they often struggle to explore the reward landscape evenly: trajectories
  toward easy-to-reach regions dominate training, while hard-to-reach modes receive
  vanishing or uninformative gradients, leading to poor coverage of high-reward areas.
  We address this imbalance with Boosted GFlowNets, a method that sequentially trains
  an ensemble of GFlowNets, each optimizing a residual reward that compensates for
  the mass already captured by previous models. This residual principle reactivates
  learning signals in underexplored regions and, under mild assumptions, ensures a
  monotone non-degradation property: adding boosters cannot worsen the learned distribution
  and typically improves it. Empirically, Boosted GFlowNets achieve substantially
  better exploration and sample diversity on multimodal synthetic benchmarks and peptide
  design tasks, while preserving the stability and simplicity of standard trajectory-balance
  training. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: dall-antonia26a
month: 0
tex_title: " Boosted GFlowNets: Improving Exploration via Sequential Learning "
firstpage: 2251
lastpage: 2259
page: 2251-2259
order: 2251
cycles: false
bibtex_author: Dall'Antonia, Pedro and Silva, Tiago and de Souza, Daniel Augusto and
  Mattos, C{\'e}sar Lincoln and Mesquita, Diego
author:
- given: Pedro
  family: Dall’Antonia
- given: Tiago
  family: Silva
- given: Daniel Augusto
  family: Souza
  prefix: de
- given: César Lincoln
  family: Mattos
- given: Diego
  family: Mesquita
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
pdf: https://raw.githubusercontent.com/mlresearch/v300/main/assets/dall-antonia26a/dall-antonia26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
