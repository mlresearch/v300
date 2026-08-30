---
title: " Securing Model Weights Against Eavesdropping Adversaries in Federated Learning
  Using Quantization "
openreview: MSoLL2ehax
abstract: " While security research in Federated Learning (FL) has predominantly focused
  on protecting client data, the \\emph{confidentiality of the model parameters} themselves
  represents a critical and underexplored vulnerability. This work addresses model
  reconstruction attacks by passive eavesdroppers, a threat present in common update
  strategies like transmitting full models or model increments. To our knowledge,
  we are the first to repurpose dynamic uniform quantization as a dedicated defense
  for model confidentiality. Our lightweight, architecture-agnostic approach combines
  low-bit quantization with an adaptive clipping rule to thwart reconstruction attacks,
  even under warm adversary initialization. We provide theoretical guarantees establishing
  that our defense offers persistent, non-zero protection in both protocols. Across
  extensive experiments on CIFAR-10 and CIFAR-100, with up to 1000 clients in heterogeneous
  settings, our method reduces the adversary’s test accuracy to near-random levels
  while maintaining global accuracy within 4% of the unquantized baseline. Our findings
  establish that repurposing quantization is a simple yet highly effective strategy
  for securing the largely overlooked area of model confidentiality in FL. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chakrabarti26a
month: 0
tex_title: " Securing Model Weights Against Eavesdropping Adversaries in Federated
  Learning Using Quantization "
firstpage: 3970
lastpage: 3978
page: 3970-3978
order: 3970
cycles: false
bibtex_author: Chakrabarti, Kushal and Maity, Dipankar
author:
- given: Kushal
  family: Chakrabarti
- given: Dipankar
  family: Maity
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
pdf: https://raw.githubusercontent.com/mlresearch/v300/main/assets/chakrabarti26a/chakrabarti26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
