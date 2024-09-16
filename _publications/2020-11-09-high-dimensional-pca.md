---
title: "High Dimensional PCA: A New Model Selection Criterion"
collection: publications
category: preprints
permalink: /publication/2020-11-09-high-dimensional-pca
excerpt: 'This paper investigates model selection criteria in high-dimensional PCA, focusing on the Akaike Information Criterion (AIC) and its consistency under varying conditions of eigenvalue separation.'
date: 2020-11-09
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/abs/2011.04470'
citation: 'Abhinav Chakraborty, Soumendu Sundar Mukherjee, Arijit Chakrabarti. (2020). "High Dimensional PCA: A New Model Selection Criterion." <i>arXiv preprint arXiv:2011.04470</i>.'
---

Given a random sample from a multivariate population, estimating the number of large eigenvalues of the population covariance matrix is an important problem in Statistics with wide applications in many areas. In the context of Principal Component Analysis (PCA), this number determines the linear combinations of the original variables that exhibit the most variation.

In this paper, we study the high-dimensional asymptotic regime, where the number of variables grows at the same rate as the number of observations. We utilize the spiked covariance model proposed by Johnstone (2001), reducing the problem to model selection. Our focus is on the Akaike Information Criterion (AIC), known to be strongly consistent from the work of Bai et al. (2018). However, Bai et al. (2018) requires a "gap condition" that ensures the dominant eigenvalues are above a threshold larger than the BBP threshold (Baik et al., 2005), both depending on the limiting ratio of the number of variables and observations.

We explore whether strong consistency of AIC can still hold when the "gap" is made smaller. We show that strong consistency under an arbitrarily small gap is achievable if the penalty term of AIC is suitably altered based on the target gap. Furthermore, we demonstrate that an intuitive alteration of the penalty term can result in the gap being exactly zero, although in this case, we only achieve weak consistency.

[PDF](https://arxiv.org/abs/2011.04470)
