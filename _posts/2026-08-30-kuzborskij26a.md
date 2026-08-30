---
title: " Low-Rank Bias, Weight Decay, and Model Merging in Neural Networks "
openreview: EjOV1vJfGi
abstract: " We explore the low-rank structure of the weight matrices in neural networks
  at the stationary points (limiting solutions of optimization algorithms) with $L2$
  regularization (also known as weight decay). We show several properties of such
  deep neural networks, induced by $L2$ regularization. In particular, for a stationary
  point we show alignment of the parameters and the gradient, norm preservation across
  layers, and low-rank bias: properties previously known in the context of solutions
  of gradient descent/flow type algorithms.  Experiments show that the assumptions
  made in the analysis only mildly affect the observations. In addition, we investigate
  a multitask learning phenomenon enabled by $L2$ regularization and low-rank bias.
  In particular, we show that if two networks are trained, such that the inputs in
  the training set of one network are approximately orthogonal to the inputs in the
  training set of the other network, the new network obtained by simply summing the
  weights of the two networks will perform as well on both training sets as the respective
  individual networks.  We demonstrate this for shallow ReLU neural networks trained
  by gradient descent, as well as deep linear networks trained by gradient flow. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: kuzborskij26a
month: 0
tex_title: " Low-Rank Bias, Weight Decay, and Model Merging in Neural Networks "
firstpage: 460
lastpage: 468
page: 460-468
order: 460
cycles: false
bibtex_author: Kuzborskij, Ilja and Abbasi-Yadkori, Yasin
author:
- given: Ilja
  family: Kuzborskij
- given: Yasin
  family: Abbasi-Yadkori
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
pdf: https://raw.githubusercontent.com/mlresearch/v300/main/assets/kuzborskij26a/kuzborskij26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
