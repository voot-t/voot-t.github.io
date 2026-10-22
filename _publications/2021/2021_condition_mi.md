---
title: "Discovering Diverse Solutions in Deep Reinforcement Learning by Maximizing State-Action-Based Mutual Information"
collection: publications
category: manuscripts
permalink: /publications/2021_condition_mi
venue: 'Neural Networks journal'
date: 2022-08-01
author: 'Takayuki Osa, Voot Tangkaratt, Masashi Sugiyama'
excerpt: "Takayuki Osa, Voot Tangkaratt, Masashi Sugiyama"
---

<div>
<h3>Authors</h3>
<p>
Voot Tangkaratt, Nontawat Charoenphakdee, Masashi Sugiyama
</p>
<h2>Abstract</h2>
<p>
Reinforcement learning algorithms are typically limited to learning a single solution for a specified task, even though diverse solutions often exist. Recent studies showed that learning a set of diverse solutions is beneficial because diversity enables robust few-shot adaptation. Although existing methods learn diverse solutions by using the mutual information as unsupervised rewards, such an approach often suffers from the bias of the gradient estimator induced by value function approximation. In this study, we propose a novel method that can learn diverse solutions without suffering the bias problem. In our method, a policy conditioned on a continuous or discrete latent variable is trained by directly maximizing the variational lower bound of the mutual information, instead of using the mutual information as unsupervised rewards as in previous studies. Through extensive experiments on robot locomotion tasks, we demonstrate that the proposed method successfully learns an infinite set of diverse solutions by learning continuous latent variables, which is more challenging than learning a finite number of solutions. Subsequently, we show that our method enables more effective few-shot adaptation compared with existing methods. 
</p>
</div>

[Download paper](https://www.sciencedirect.com/science/article/abs/pii/S0893608022001393)
