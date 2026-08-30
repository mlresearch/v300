---
title: " Clustering-Based Edge Augmentation for Minimizing the Kirchhoff Index "
openreview: 6lTwYO9dZk
abstract: " The Kirchhoff index ($\\mathcal{K}_{G}$), defined as the sum of effective
  resistances over all pairs of nodes in a connected undirected graph $G$, is a fundamental
  metric for real-world networks. It corresponds to average power consumption in electrical
  circuits, average commute time of random walks, and more relevantly to optimization,
  is equal to $\\text{Tr}(\\mathcal{L}^{\\dagger})$, where $\\mathcal{L}$ is the graph
  Laplacian. In this paper, we study the problem of augmenting a given graph by adding
  $k$ edges to minimize the Kirchhoff index. The problem was introduced in a work
  of Ghosh, Boyd, and Saberi (2008), and is known to be NP-hard; the state-of-the-art
  algorithms mostly employ greedy heuristics and have very weak guarantees. We design
  novel algorithms and show bi-criteria approximation guarantees, i.e., the algorithm
  adds $c \\cdot k$ edges and obtains an $\\alpha$ factor approximation to the optimum
  objective value with $k$ edges. Specifically, an algorithm based on $k$-median clustering
  with penalties achieves $c=2$ and $\\alpha = O(k)$. By using known submodularity
  ideas, we extend this to achieve $c=O(\\log k)$ and $\\alpha=(4+\\epsilon)$. The
  problem corresponds to an augmentation version of the classic A-optimal experimental
  design problem in statistics. We also prove strong integrality gaps for the natural
  convex relaxation and demonstrate the performance of our algorithm on real and synthetic
  graphs. "
layout: inproceedings
series: Proceedings of Machine Learning Research
publisher: PMLR
issn: 2640-3498
id: yalamanchili26a
month: 0
tex_title: " Clustering-Based Edge Augmentation for Minimizing the Kirchhoff Index "
firstpage: 3745
lastpage: 3753
page: 3745-3753
order: 3745
cycles: false
bibtex_author: Yalamanchili, Prasanth and Bhaskara, Aditya
author:
- given: Prasanth
  family: Yalamanchili
- given: Aditya
  family: Bhaskara
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
pdf: https://raw.githubusercontent.com/mlresearch/v300/main/assets/yalamanchili26a/yalamanchili26a.pdf
extras: []
# Format based on Martin Fenner's citeproc: https://blog.front-matter.io/posts/citeproc-yaml-for-bibliographies/
---
