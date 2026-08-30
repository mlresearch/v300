---
title: " Support Basis: Fast Attention Beyond Bounded Entries "
openreview: IgpnZIGFsD
abstract: " Large language models (LLMs) have demonstrated remarkable performance
  across a wide range of tasks. However, the quadratic complexity of softmax attention
  remains a central bottleneck that limits their scalability. Alman and Song (NeurIPS
  2023a; NeurIPS 2024a) proposed sub-quadratic time algorithms for attention inference
  and training, respectively, but they rely on the restrictive \\textbf{bounded-entry
  assumption}. We show that this assumption rarely holds in practice, which significantly
  limits their applicability to modern LLMs. In this paper, we introduce \\textbf{support-basis
  decomposition}, a new technique for accurate and efficient attention inference and
  training \\textbf{without} the bounded-entry assumption. We empirically show that
  the entries of the query and key matrices exhibit sub-Gaussian behavior. Leveraging
  this widely observed property, we perform exact computation on sparse components
  and polynomial approximation on dense components. Without relying on restrictive
  assumptions, we theoretically show that our algorithm achieves sub-quadratic runtime
  while matching the approximation error of prior work, and we empirically validate
  its computational efficiency and downstream task performance. We further generalize
  our method to a multi-threshold setting that eliminates all distributional assumptions,
  providing the first theoretical justification for the empirical success of polynomial
  attention. Moreover, we show that softmax attention can be closely approximated
  by multiple polynomial attentions with significantly smaller $\\ell_p$ error. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: aliakbarpour26a
month: 0
tex_title: " Support Basis: Fast Attention Beyond Bounded Entries "
firstpage: 325
lastpage: 333
page: 325-333
order: 325
cycles: false
bibtex_author: Aliakbarpour, Maryam and Braverman, Vladimir and Yin, Junze and Zhang,
  Haochen
author:
- given: Maryam
  family: Aliakbarpour
- given: Vladimir
  family: Braverman
- given: Junze
  family: Yin
- given: Haochen
  family: Zhang
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
pdf: https://raw.githubusercontent.com/mlresearch/v300/main/assets/aliakbarpour26a/aliakbarpour26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
