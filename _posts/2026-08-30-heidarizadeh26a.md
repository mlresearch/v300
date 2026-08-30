---
title: " Confidence-Guided Self-Training for Gradual Domain Adaptation "
openreview: E7GKOyRPRl
abstract: " Domain adaptation addresses the challenge of distributional shift between
  a labeled source domain and an unlabeled target domain. In gradual domain adaptation
  (GDA), the shift is assumed to occur through a sequence of intermediate domains,
  enabling smoother adaptation. A popular approach in this setting is self-training,
  where a model iteratively generates pseudo-labels for unlabeled data. However, pseudo-labeling
  errors can accumulate across rounds, especially under large shift, undermining generalization.
  We develop a theoretical framework for self-training under gradual domain shift
  that explicitly quantifies and controls the pseudo-labeling error incurred at each
  round. Our first result is a modular generalization bound that decomposes the excess
  target risk into \\emph{coverage}, \\emph{pseudo-label error}  $(\\varepsilon_k)$
  on the accepted set, domain shift, sample complexity, and regularization. Unlike
  prior bounds, our analysis separates the coverage penalty (due to rejecting inputs)
  from the pseudo-label error (controlled by confidence calibration or margin filtering,
  including Tsybakov-type noise via margin decay or calibration assumptions). We also
  provide the first theoretical justification for percentile (quantile) thresholding
  schemes used in practice: such schedules directly control coverage while tightening
  $\\varepsilon_k$, yielding a principled coverage–noise tradeoff. Under mild conditions,
  both terms accumulate only logarithmically, leading to improved generalization.
  We validate these insights across multiple GDA benchmarks, using both observed and
  OT-generated intermediate domains. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: heidarizadeh26a
month: 0
tex_title: " Confidence-Guided Self-Training for Gradual Domain Adaptation "
firstpage: 3934
lastpage: 3942
page: 3934-3942
order: 3934
cycles: false
bibtex_author: Heidarizadeh, Akram and Awad, Akram and Cai, HanQin and Atia, George
  K.
author:
- given: Akram
  family: Heidarizadeh
- given: Akram
  family: Awad
- given: HanQin
  family: Cai
- given: George K.
  family: Atia
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
pdf: https://raw.githubusercontent.com/mlresearch/v300/main/assets/heidarizadeh26a/heidarizadeh26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
