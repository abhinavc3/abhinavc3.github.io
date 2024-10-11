---
title: "Optimal Differentially Private Ranking from Pairwise Comparisons"
collection: publications
category: preprints
permalink: /publication/2023-09-25-optimal-dp-ranking
excerpt: 'This paper proposes optimal differentially private algorithms for ranking from noisy pairwise comparisons, establishing minimax rates for both parametric and nonparametric settings.'
date: 2023-09-25
venue: 'Technical Report'
paperurl: /files/DP_Ranking_Main.pdf
citation: 'T. Tony Cai, Abhinav Chakraborty, Yichen Wang. (2023). "Optimal Differentially Private Ranking from Pairwise Comparisons.".'
---

Ranking from pairwise comparisons is a well-studied problem with many applications such as recommendation systems, education, and social sciences. In these applications, data privacy often stands as a paramount concern. This paper studies the problem of ranking a set of items with privacy guarantees based on noisy pairwise comparison data. We investigate the optimality of differentially private algorithms for ranking from pairwise comparisons in both parametric and nonparametric settings. Novel differentially private algorithms are proposed, and their minimax rate optimality is established.
Under parametric assumptions that encompass the Bradley-Terry-Luce model, we introduce a randomly perturbed maximum likelihood estimator and establish its optimality. When the parametric model is not assumed, we show that ranking by noisy counts of wins can recover the true ranks with high probability. Matching lower bounds are established by an entry-wise version of the score attack technique, as well as a differentially private Fano’s inequality. Simulation studies and real data analyses are conducted to demonstrate the numerical performance of our algorithms.

[PDF](/files/DP_Ranking_Main.pdf)
