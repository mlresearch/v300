---
title: " Optimistic Reinforcement Learning with Quantile Objectives "
openreview: 8MuJDoP8XK
abstract: " Reinforcement Learning (RL) has achieved tremendous success in recent
  years. However, the classical foundations of RL do not account for the risk sensitivity
  of the objective function, which is critical in various fields, including healthcare,
  finance, etc. A popular approach to incorporate risk sensitivity is to optimize
  a specific quantile of the cumulative reward distribution. In this paper, we develop
  UCB-QRL, an optimistic learning algorithm for the $\\tau$-quantile objective in
  finite-horizon Markov decision processes (MDPs). UCB-QRL is an iterative algorithm
  in which, at each iteration, we first estimate the underlying transition probability
  and then optimize the quantile value function over a confidence ball around this
  estimate. Here, we show that UCB-QRL yields high-probability regret bounds $\\mathcal
  O\\left((2/\\kappa)^HH\\sqrt{SATH\\log(2SATH/\\delta)}\\right)$ in the episodic
  setting with $S$ states, $A$ actions, $T$ episodes, and $H$ horizons. Here, $\\kappa>0$
  is a problem-dependent constant that captures the sensitivity of the underlying
  MDP’s quantile value. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: alipour-vaezi26a
month: 0
tex_title: " Optimistic Reinforcement Learning with Quantile Objectives "
firstpage: 3601
lastpage: 3609
page: 3601-3609
order: 3601
cycles: false
bibtex_author: Alipour-Vaezi, Mohammad and Zhong, Huaiyang and Tsui, Kwok-leung and
  Khodadadian, Sajad
author:
- given: Mohammad
  family: Alipour-Vaezi
- given: Huaiyang
  family: Zhong
- given: Kwok-leung
  family: Tsui
- given: Sajad
  family: Khodadadian
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
pdf: https://raw.githubusercontent.com/mlresearch/v300/main/assets/alipour-vaezi26a/alipour-vaezi26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
