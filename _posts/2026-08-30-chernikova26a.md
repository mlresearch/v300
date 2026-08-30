---
title: " Robustness and Generalization in Uncertainty-Aware Message Passing Neural
  Networks "
openreview: BcqtGTw9OZ
abstract: " Existing theoretical guarantees for message passing neural networks (MPNNs)
  assume deterministic node features. We address a more realistic scenario where noise
  or finite measurement precision introduces uncertainties in node feature values.
  First, we quantify uncertainty by propagating the moments of node-feature distributions
  through the MPNN architecture. To propagate moments through activation functions,
  we use the Taylor expansion and the pseudo-Taylor polynomial expansion. We then
  use the resulting node embedding distributions to analytically derive probabilistic
  adversarial robustness certificates for node classification tasks against L2-bounded
  perturbations of node features. Second, we model node features as multivariate random
  variables and introduce Feature Convolution Distance $FCD_p$, a pseudometric based
  on the Wasserstein distance. $FCD_p$ corresponds to the discriminative power of
  MPNNs at the node level. We show that MPNNs are globally Lipschitz continuous functions
  with respect to the pseudometric $FCD_p$. Using the covering number of the resulting
  pseudometric space, which is a subset of the Wasserstein space, we derive generalization
  bounds for MPNNs with uncertainties in node features. Together, these two complementary
  approaches—moment propagation for adversarial robustness and $FCD_p$ on the subset
  of the Wasserstein space for generalization—establish a unified theoretical framework
  that comprehensively addresses MPNN reliability under node feature uncertainty. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chernikova26a
month: 0
tex_title: " Robustness and Generalization in Uncertainty-Aware Message Passing Neural
  Networks "
firstpage: 3826
lastpage: 3834
page: 3826-3834
order: 3826
cycles: false
bibtex_author: Chernikova, Alesia and Laber, Moritz and Sabhahit, Narayan G. and Eliassi-Rad,
  Tina
author:
- given: Alesia
  family: Chernikova
- given: Moritz
  family: Laber
- given: Narayan G.
  family: Sabhahit
- given: Tina
  family: Eliassi-Rad
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
pdf: https://raw.githubusercontent.com/mlresearch/v300/main/assets/chernikova26a/chernikova26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
