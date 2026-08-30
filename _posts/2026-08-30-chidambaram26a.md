---
title: " Direct Preference Optimization with Unobserved Preference Heterogeneity:
  The Necessity of Ternary Preferences "
openreview: 7RFcY3ljMO
abstract: " Reinforcement Learning from Human Feedback (RLHF) has become central to
  aligning large language models with human values, typically by first learning a
  reward model from preference data which is then used to update the model with reinforcement
  learning. Recent alternatives such as Direct Preference Optimization (DPO) simplify
  this pipeline by directly optimizing on preferences. However, both approaches often
  assume uniform annotator preferences and rely on binary comparisons, overlooking
  two key limitations: the diversity of human evaluators and the limitations of pairwise
  feedback. In this work, we address both these issues. First, we connect preference
  learning in RLHF with the econometrics literature and show that binary comparisons
  are insufficient for identifying latent user preferences from finite user data and
  infinite users, while (even incomplete) rankings over three or more responses ensure
  identifiability. Second, we introduce methods to incorporate heterogeneous preferences
  into alignment algorithms. We develop an Expectation-Maximization adaptation of
  DPO that discovers latent annotator types and trains a mixture of LLMs accordingly.
  Then we propose an aggregation algorithm using a min-max regret fairness criterion
  to produce a single generative policy with equitable performance guarantees. Together,
  these contributions establish a theoretical and algorithmic framework for fairness
  and personalization for diverse users in generative model alignment. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: chidambaram26a
month: 0
tex_title: " Direct Preference Optimization with Unobserved Preference Heterogeneity:
  The Necessity of Ternary Preferences "
firstpage: 4555
lastpage: 4563
page: 4555-4563
order: 4555
cycles: false
bibtex_author: Chidambaram, Keertana and Seetharaman, Karthik Vinay and Syrgkanis,
  Vasilis
author:
- given: Keertana
  family: Chidambaram
- given: Karthik Vinay
  family: Seetharaman
- given: Vasilis
  family: Syrgkanis
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
pdf: https://raw.githubusercontent.com/mlresearch/v300/main/assets/chidambaram26a/chidambaram26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
