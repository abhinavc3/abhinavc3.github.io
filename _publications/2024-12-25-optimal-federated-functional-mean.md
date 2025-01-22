---
title: "Optimal Federated Learning for Functional Mean Estimation under Heterogeneous Privacy Constraints"
collection: publications
category: preprints
permalink: /publication/2024-12-25-optimal-federated-functional-mean
excerpt: 'This paper examines the statistical optimality of federated learning for functional mean estimation under heterogeneous privacy constraints, addressing both theoretical and practical aspects.'
date: 2024-12-25
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/abs/2412.18992'
citation: 'Tony Cai, Abhinav Chakraborty, Lasse Vuursteen. (2024). "Optimal Federated Learning for Functional Mean Estimation under Heterogeneous Privacy Constraints." <i>arXiv preprint arXiv:2412.18992v2</i>.'
---

This paper addresses the challenge of estimating the mean of random functions from discretely sampled data within a federated learning framework while adhering to rigorous differential privacy (DP) constraints. The study introduces a novel federated learning model to account for heterogeneity in the number of individuals, measurement points, and privacy budgets across multiple servers.

Two sampling designs are analyzed:  
1. **Common Design**: All individuals are sampled at the same design points.  
2. **Independent Design**: Individuals are sampled at unique sets of random design points.

For both designs, the authors establish minimax upper and lower bounds on the estimation error for the mean function under federated DP constraints. These results quantify the privacy-accuracy trade-offs inherent in distributed statistical inference. 

The authors propose optimal algorithms that achieve these bounds, demonstrating their practical utility through simulations and real-world applications. The paper contributes to the understanding of privacy-preserving statistical analysis in federated environments, offering foundational insights for developing efficient methods in distributed settings.

[PDF](https://arxiv.org/abs/2412.18992)
