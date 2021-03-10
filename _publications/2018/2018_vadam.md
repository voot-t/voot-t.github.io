---
title: "Fast and Scalable Bayesian Deep Learning by Weight-perturbation in Adam"
collection: publications
venue: 'International Conference on Machine Learning'
s_venue : 'ICML'
date: 2018-07-01
author: 'Mohammad Khan, Didrik Nielsen, Voot Tangkaratt, Wu Lin, Yarin Gal, Akash Srivastava'
slug: "fast-and-scalable-bayesian-deep-learning-by-weight-perturbation-in-adam"
---

<div>
<h2>Abstract</h2>
<p>
Uncertainty computation in deep learning is essential to design robust and reliable systems. Variational inference (VI) is a promising approach for such computation, but requires more effort to implement and execute compared to maximum-likelihood methods. In this paper, we propose new natural-gradient algorithms to reduce such efforts for Gaussian mean-field VI. Our algorithms can be implemented within the Adam optimizer by perturbing the network weights during gradient evaluations, and uncertainty estimates can be cheaply obtained by using the vector that adapts the learning rate. This requires lower memory, computation, and implementation effort than existing VI methods, while obtaining uncertainty estimates of comparable quality. Our empirical results confirm this and further suggest that the weight-perturbation in our algorithm could be useful for exploration in reinforcement learning and stochastic optimization.
</p>
</div>

[Download paper](http://proceedings.mlr.press/v80/khan18a.html)

[Download source code](https://github.com/emtiyaz/vadam)
