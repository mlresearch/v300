---
title: " In-Context Learning for Discrete Optimal Transport: Can Transformers Sort? "
openreview: hwIs2DCYFU
abstract: " The rapid growth of model sizes and training datasets has created a strong
  demand for \\emph{test-time compute}—the ability to perform inference without additional
  training. At the core of test-time compute is \\emph{in-context learning} (ICL),
  an emerging capability of large language models (LLMs) that enables them to perform
  statistical inference directly at test time. Recent progress has shed light on the
  mechanisms underlying in-context learning in statistical tasks: language models
  can implement linear regression and classification by iteratively extracting features
  at test time. This naturally raises a broader question: \\emph{Can we analyze ICL
  beyond statistical learning and extend it to discrete algorithmic tasks relevant
  to NLP?} One of the fundamental tasks in NLP can be formulated as discrete optimal
  transport: matching tokens, with applications ranging from machine translation to
  mixture-of-experts routing. We show that transformers with softmax self-attention
  can solve discrete optimal transport via in-context learning when the model parameters
  are fixed and only the input length and data distribution vary. One implication
  of this result is that transformers can approximately sort lists of arbitrary length
  with a provable approximation guarantee. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: daneshmand26a
month: 0
tex_title: " In-Context Learning for Discrete Optimal Transport: Can Transformers
  Sort? "
firstpage: 847
lastpage: 855
page: 847-855
order: 847
cycles: false
bibtex_author: Daneshmand, Hadi
author:
- given: Hadi
  family: Daneshmand
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
pdf: https://raw.githubusercontent.com/mlresearch/v300/main/assets/daneshmand26a/daneshmand26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
