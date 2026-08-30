---
title: " Preconditioned Attention: Enhancing Efficiency in Transformer Blocks "
openreview: SoFvbfAbRs
abstract: " Central to the success of Transformers is the attention block, which effectively
  models global dependencies among input tokens associated to a dataset. However,
  we theoretically demonstrate that standard attention mechanisms in transformers
  often produce ill-conditioned matrices with large condition numbers. This ill-conditioning
  is a well-known obstacle for gradient-based optimizers, leading to inefficient training.
  To address this issue, we introduce preconditioned attention, a novel approach that
  incorporates a conditioning matrix into each attention head. Our theoretical analysis
  shows that this method significantly reduces the condition number of attention matrices,
  resulting in better-conditioned matrices that improve optimization. Conditioned
  attention serves as a simple drop-in replacement for a wide variety of attention
  mechanisms in the literature. We validate the effectiveness of preconditioned attention
  across a diverse set of transformer applications, including image classification,
  object detection, instance segmentation, long sequence modeling and language modeling. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: saratchandran26a
month: 0
tex_title: " Preconditioned Attention: Enhancing Efficiency in Transformer Blocks "
firstpage: 1153
lastpage: 1161
page: 1153-1161
order: 1153
cycles: false
bibtex_author: Saratchandran, Hemanth
author:
- given: Hemanth
  family: Saratchandran
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
pdf: https://raw.githubusercontent.com/mlresearch/v300/main/assets/saratchandran26a/saratchandran26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
