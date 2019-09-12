---
title: "Convergence of Adversarial Training in Overparametrized Networks"
collection: publications
permalink: /publication/advtrain
excerpt: 'For overparameterized neural network, we prove that adversarial training can converge to global minima (with loss 0).'
date: 2019-6-19
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/1906.07916'
---
# Abstract

Neural networks are vulnerable to adversarial examples, i.e. inputs that are imperceptibly perturbed from natural data and yet incorrectly classified by the network. Adversarial training, a heuristic form of robust optimization that alternates between minimization and maximization steps, has proven to be among the most successful methods to train networks that are robust against a pre-defined family of perturbations. This paper provides a partial answer to the success of adversarial training. When the inner maximization problem can be solved to optimality, we prove that adversarial training finds a network of small robust train loss. When the maximization problem is solved by a heuristic algorithm, we prove that adversarial training finds a network of small robust surrogate train loss. The analysis technique leverages recent work on the analysis of neural networks via Neural Tangent Kernel (NTK), combined with online-learning when the maximization is solved by a heuristic, and the expressiveness of the NTK kernel in the ℓ∞-norm.