---
title: " TexTSC: Class-Texture Preserving Data Condensation for Time Series Classification "
openreview: wS87abrnaZ
abstract: " Dataset condensation seeks to generate a small set of synthetic examples
  that can replace large real datasets for training, but existing methods for time
  series often rely on unstable training-trajectory matching or capture only limited
  signal structure. We present TexTSC, a condensation framework that preserves class
  structure using spectro-temporal second-order statistics instead of trajectory replay.
  TexTSC models each class’s “texture” as the co-activation pattern among intermediate
  teacher features, aligning Gram matrices of activations in time to capture temporal
  correlations and in frequency to capture spectral envelopes and harmonics. A short-lag
  autocorrelation term stabilizes local rhythm, while a lightweight gradient anchor
  at the final layer ensures discriminative power. TexTSC optimizes synthetic sequences
  directly, remains model-agnostic, and requires only closed-form statistics, making
  it simple and stable. Experiments on standard benchmarks show that TexTSC produces
  compact datasets that retain class-conditional structure and achieve higher classification
  accuracy than first-order or single-domain baselines. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: hosseinzadeh26a
month: 0
tex_title: " TexTSC: Class-Texture Preserving Data Condensation for Time Series Classification "
firstpage: 4222
lastpage: 4230
page: 4222-4230
order: 4222
cycles: false
bibtex_author: Hosseinzadeh, Pouya and Li, Peiyu and Bahri, Omar and Boubrahimi, Soukaina
  Filali and Hamdi, Shah Muhammad
author:
- given: Pouya
  family: Hosseinzadeh
- given: Peiyu
  family: Li
- given: Omar
  family: Bahri
- given: Soukaina Filali
  family: Boubrahimi
- given: Shah Muhammad
  family: Hamdi
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
pdf: https://raw.githubusercontent.com/mlresearch/v300/main/assets/hosseinzadeh26a/hosseinzadeh26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
