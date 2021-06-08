---
title: "Global optimization for l0-norm-based sparse solutions to least squares problems"
speaker: "Sébastien Bourguignon"
affiliation: "École Centrale de Nantes, LS2N, SIMS team"
date: 2021-04-09 11:00
online: "https://eu.bbcollab.com/guest/18aee800e2e04720b0db85013390c166"
image: "seminars/sebastien-bourguignon/sebastien-bourguignon.jpp"
feature_image: "sebastien-bourguignon.jpg"
perso: "http://pagesperso.ls2n.fr/~bourguignon-s/"
speakerdeck: https://speakerdeck.com/s3_seminar/sebastien-bourguignon
aside: true
---

<div style="text-align:center">
<script async class="speakerdeck-embed" data-id="1ecbaa2a8a8047b086bbca1333693e8a" data-ratio="1.33333333333333" src="//speakerdeck.com/assets/embed.js"></script>
</div>

###### Abstract

Finding solutions to least- squares problems with low cardinality (with small l0 "norm") has found many applications, including sparsity-enhancing inverse problems in signal processing, subset selection in statistics, and cardinality-constrained portfolio optimization. This problem is NP-hard, therefore most works propose suboptimal (continuous relaxation or greedy) methods that are able to address high-dimensional problems. On the other hand, several recent works studied the global optimization of l0-norm problems through the mixed integer programming (MIP) reformulation of the l0 norm. Resolution is performed via MIP solvers, which essentially implement branch-and-bound methods.

We propose branch-and-bound algorithms which are specifically built for three possible formulations: cardinality-constrained and cardinality-penalized least squares, and cardinality minimization under a limited error constraint. A specific tree exploration strategy is built, inspired by forward greedy methods in stepwise regression. We then show that the relaxation problems involved at each node of the search tree can be reformulated as a l1-norm optimization problem. We propose a dedicated algorithm for such problems, based on the homotopy continuation principle. Branch-and-bound algorithms are then constructed, which are guaranteed to find the optimal subset, without resorting to MIP reformulations nor binary variables.

The obtained certified solutions are shown to better estimate sparsity patterns than standard methods on simulated problems involving 1 000 unknowns and up to a few tens of non-zero components. For problems with higher complexity, unguaranteed solutions obtained by limiting the computing time are also shown to provide more satisfactory estimates. The resulting global optimization procedure is finally shown to strongly improve over the CPLEX MIP solver in terms of computing time.

Joint work with Ramzi Ben Mhenni and Jordan Ninin.

###### References

[1] Ramzi Ben Mhenni, Sébastien Bourguignon, Marcel Mongeau, Jordan Ninin, Hervé Carfantan. Sparse Branch and Bound for Exact Optimization of L0-Norm Penalized Least Squares. IEEE International Conference on Acoustics, Speech and Signal Processing, May 2020, Barcelona, Spain. https://hal.archives-ouvertes.fr/hal-02564594

[2] Ramzi Ben Mhenni, Sébastien Bourguignon, Jordan Ninin. Global Optimization for Sparse Solutio nof Least Squares Problem, submitted. https://hal.archives-ouvertes.fr/hal-02066368

###### Biography

Sébastien Bourguignon is an assistant professor (HDR) at Ecole Centrale de Nantes since 2011. His research focuses on the design of signal and image processing algorithms for the resolution of inverse problems encountered in various fields of science and engineering, including ultrasonic imaging, microwave imaging or hyperspectral imaging, in particular for nondestructive testing, planetary science and astronomy. He is particularly interested in exploiting information based on sparsity, both in the physical modeling of data and in the related computational aspects. He is currently the coordinator of the MIMOSA "young researchers" project (Mixed Integer programming Methods for Optimization of Sparse Approximation criteria) funded by the French national agency (2017-2021).
