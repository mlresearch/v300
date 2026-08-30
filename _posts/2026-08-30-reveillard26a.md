---
title: " Minimizing Human Intervention in Online Classification "
openreview: cWb7dddPyI
abstract: " Training or fine-tuning large language model (LLM)–based systems often
  requires costly human feedback, yet there is limited understanding of how to minimize
  such intervention while maintaining strong error guarantees. We study this problem
  for LLM-based classification systems in an active learning framework: an agent sequentially
  labels $d$-dimensional query embeddings drawn i.i.d. from an unknown distribution
  by either calling a costly expert or guessing with no feedback, with the goal of
  minimizing regret relative to an oracle with free expert access. When the horizon
  $T$ is at least exponential in the embedding dimension $d$, the geometry of the
  class regions can be learned. In this regime, we propose the Conservative Hull-based
  Classifier (CHC), which maintains convex hulls of expert-labeled queries and calls
  the expert when a query lands outside all known hulls. CHC attains $\\mathcal{O}(\\log^d
  T)$ regret in $T$ and is minimax optimal for $d=1$. Otherwise, the geometry cannot
  be reliably learned in general. We show that for queries drawn from a subgaussian
  mixture and $T \\le e^d$, a Center-based Classifier (CC) achieves regret proportional
  to $N\\log{N}$ where $N$ is the number of labels. To bridge these regimes, we introduce
  the Generalized Hull-based Classifier (GHC), a practical extension of CHC that enables
  more aggressive guessing via a tunable parameter. Our approach is validated on real-world
  question-answering datasets using state-of-the-art text embedding models. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: reveillard26a
month: 0
tex_title: " Minimizing Human Intervention in Online Classification "
firstpage: 2917
lastpage: 2925
page: 2917-2925
order: 2917
cycles: false
bibtex_author: R{\'e}veillard, William and Saketos, Vasileios and Proutiere, Alexandre
  and Combes, Richard
author:
- given: William
  family: Réveillard
- given: Vasileios
  family: Saketos
- given: Alexandre
  family: Proutiere
- given: Richard
  family: Combes
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
pdf: https://raw.githubusercontent.com/mlresearch/v300/main/assets/reveillard26a/reveillard26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
