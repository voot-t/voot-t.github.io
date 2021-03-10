---
title: "Direct Estimation of the Derivative of Quadratic Mutual Information with Application in Supervised Dimension Reduction"
collection: publications
venue: 'Neural Computation journal'
date: 2017-08-01
author: 'Voot Tangkaratt, Hiroaki Sasaki, Masashi Sugiyama'
slug: "direct-estimation-of-the-derivative-of-quadratic-mutual-information-with-application-in-supervised-dimension-reduction"
---

<div>
<h2>Abstract</h2>
<p>
A typical goal of linear-supervised dimension reduction is to find a low-dimensional subspace of the input space such that the projected input variables preserve maximal information about the output variables. The dependence-maximization approach solves the supervised dimension-reduction problem through maximizing a statistical dependence between projected input variables and output variables. A well-known statistical dependence measure is mutual information (MI), which is based on the Kullback-Leibler (KL) divergence. However, it is known that the KL divergence is sensitive to outliers. Quadratic MI (QMI) is a variant of MI based on the distance, which is more robust against outliers than the KL divergence, and a computationally efficient method to estimate QMI from data, least squares QMI (LSQMI), has been proposed recently. For these reasons, developing a supervised dimension-reduction method based on LSQMI seems promising. However, not QMI itself but the derivative of QMI is needed for subspace search in linear-supervised dimension reduction, and the derivative of an accurate QMI estimator is not necessarily a good estimator of the derivative of QMI. In this letter, we propose to directly estimate the derivative of QMI without estimating QMI itself. We show that the direct estimation of the derivative of QMI is more accurate than the derivative of the estimated QMI. Finally, we develop a linear-supervised dimension-reduction algorithm that efficiently uses the proposed derivative estimator and demonstrate through experiments that the proposed method is more robust against outliers than existing methods.
</p>
</div>

[Download paper](https://arxiv.org/abs/1508.01019)
