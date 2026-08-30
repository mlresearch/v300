---
title: " Multi-Agent Lipschitz Bandits "
openreview: NU614Ne4k3
abstract: " We study the decentralized multi-player stochastic bandit problem over
  a continuous, Lipschitz-structured action space where hard collisions yield zero
  reward. Our objective is to design a communication-free policy that maximizes collective
  reward, while separating coordination costs from learning costs. We propose a modular
  protocol that first solves the multi-agent coordination problem by identifying and
  seating players on distinct, high-value regions via a novel maxima-directed search
  and then decouples the problem into $N$ independent single-player Lipschitz bandits.
  In the consensus regime, we obtain an end-to-end regret bound whose dominant learning
  term is \\(\\tilde{O}(T^{(d+1)/(d+2)})\\), matching the single-player Lipschitz
  rate; the upfront coordination cost is horizon-independent at fixed confidence and
  only polylogarithmic in \\(T\\){in} the expected-regret form. Under an additional
  public coverage/scheduling assumption for the epochic extension, we also obtain
  a gap-free \\(\\tilde{O}(T^{(d+1)/(d+2)})\\){guarantee}. We further derive a matching
  lower bound for the dominant learning term and extend the framework to general distance-threshold
  collision models. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chakraborty26b
month: 0
tex_title: " Multi-Agent Lipschitz Bandits "
firstpage: 4429
lastpage: 4437
page: 4429-4437
order: 4429
cycles: false
bibtex_author: Chakraborty, Sourav and Rege, Amit Kiran and Monteleoni, Claire and
  Chen, Lijun
author:
- given: Sourav
  family: Chakraborty
- given: Amit Kiran
  family: Rege
- given: Claire
  family: Monteleoni
- given: Lijun
  family: Chen
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
pdf: https://raw.githubusercontent.com/mlresearch/v300/main/assets/chakraborty26b/chakraborty26b.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
