---
title: "A gram-gauss-newton method learning overparameterized deep neural networks for regression problems"
collection: publications
permalink: /publication/ggn
excerpt: 'A provable second-order optimization method for overparameterized network on regression problem! As light as SGD at each iteration but converge much faster than SGD for real world application.'
date: 2019-5-28
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/1905.11675'
---
# Abstract

First-order methods such as stochastic gradient descent (SGD) are currently the standard algorithm for training deep neural networks. Second-order methods, despite their better convergence rate, are rarely used in practice due to the prohibitive computational cost in calculating the second order information. In this paper, we propose a novel Gram-Gauss-Newton (GGN) algorithm to train deep neural networks for regression problems with square loss. Different from typical second-order methods that have heavy computational cost in each iteration, our proposed GGN only has minor overhead compared to first-order methods such as SGD. We also provide theoretical results to show that for sufficiently wide neural networks, the convergence rate of the GGN algorithm is quadratic. Preliminary experiments on regression tasks demonstrate that for training standard networks, the GGN algorithm converges faster and achieves better performance than SGD.