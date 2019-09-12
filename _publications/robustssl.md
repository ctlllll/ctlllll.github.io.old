---
title: "Adversarially robust generalization just requires more unlabeled data"
collection: publications
permalink: /publication/robustssl
excerpt: 'Though robust generalization need more data, we show that just more unlabeled data is enough by both theory and experiments!'
date: 2019-6-3
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/1906.00555'
---
# Abstract

Neural network robustness has recently been highlighted by the existence of adversarial examples. Many previous works show that the learned networks do not perform well on perturbed test data, and significantly more labeled data is required to achieve adversarially robust generalization. In this paper, we theoretically and empirically show that with just more unlabeled data, we can learn a model with better adversarially robust generalization. The key insight of our results is based on a risk decomposition theorem, in which the expected robust risk is separated into two parts: the stability part which measures the prediction stability in the presence of perturbations, and the accuracy part which evaluates the standard classification accuracy. As the stability part does not depend on any label information, we can optimize this part using unlabeled data. We further prove that for a specific Gaussian mixture problem illustrated by\cite {schmidt2018adversarially}, adversarially robust generalization can be almost as easy as the standard generalization in supervised learning if a sufficiently large amount of unlabeled data is provided. Inspired by the theoretical findings, we propose a new algorithm called PASS by leveraging unlabeled data during adversarial training. We show that in the transductive and semi-supervised settings, PASS achieves higher robust accuracy and defense success rate on the Cifar-10 task.