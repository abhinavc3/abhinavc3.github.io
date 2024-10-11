---
title: "Doubly Robust and Computationally Efficient High-Dimensional Variable Selection"
collection: publications
category: preprints
permalink: /publication/2024-09-14-doubly-robust-variable-selection
excerpt: 'This paper introduces the tPCM method, a doubly robust and computationally efficient approach to high-dimensional variable selection, offering improvements over existing methods such as HRT and PCM.'
date: 2024-09-14
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/abs/2409.09512'
citation: 'Abhinav Chakraborty, Jeffrey Zhang, Eugene Katsevich. (2024). "Doubly Robust and Computationally Efficient High-Dimensional Variable Selection." <i>arXiv preprint arXiv:2409.09512</i>.'
---

The variable selection problem seeks to identify which of a large set of predictors is associated with an outcome of interest, conditionally on other predictors. While extensively studied, existing methods often fall short in one or more aspects: power against complex alternatives, robustness to model misspecification, computational efficiency, or the ability to quantify evidence against individual hypotheses.

This paper presents **tower PCM (tPCM)**, a novel approach to high-dimensional variable selection that balances these trade-offs. tPCM is a doubly robust and computationally efficient method that builds on the best aspects of two existing procedures—the **holdout randomization test (HRT)** and the **projected covariance measure (PCM)**. HRT relies on many resamples with few machine learning fits, while PCM uses no resamples but requires many fits.

We show that tPCM combines the strengths of both approaches while avoiding their limitations. Theoretically, we prove the validity of tPCM and establish its asymptotic equivalence to HRT and PCM. Our extensive simulation studies demonstrate that tPCM provides significant computational savings compared to HRT and PCM, without sacrificing statistical power.

[PDF](https://arxiv.org/abs/2409.09512)
