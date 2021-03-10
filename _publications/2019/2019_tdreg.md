---
title: "TD-regularized actor-critic methods"
collection: publications
venue: 'Machine Learning journal'
date: 2019-09-01
author: 'Simone Parisi, Voot Tangkaratt, Jan Peters, Mohammad Emtiyaz Khan'
slug: "td-regularized-actor-critic-methods"
---

<div>
<h2>Abstract</h2>
<p>
Actor-critic methods can achieve incredible performance on difficult reinforcement learning problems, but they are also prone to instability. This is partly due to the interaction between the actor and critic during learning, e.g., an inaccurate step taken by one of them might adversely affect the other and destabilize the learning. To avoid such issues, we propose to regularize the learning objective of the actor by penalizing the temporal difference (TD) error of the critic. This improves stability by avoiding large steps in the actor update whenever the critic is highly inaccurate. The resulting method, which we call the TD-regularized actor-critic method, is a simple plug-and-play approach to improve stability and overall performance of the actor-critic methods. Evaluations on standard benchmarks confirm this. Source code can be found at https://github.com/sparisi/td-reg .
</p>
</div>

[Download paper](https://link.springer.com/article/10.1007/s10994-019-05788-0)
