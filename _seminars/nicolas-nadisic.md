---
title: "Matrix-wise L0-constrained Sparse Nonnegative Least Squares"
speaker: Nicolas Nadisic
affiliation: Universiteit Gent, Belgium
date: 2022-12-02 14:00
perso: http://nicolasnadisic.xyz/
online: Salle des séminaires du L2S
aside: true
---

###### Abstract

Nonnegative least squares problems with multiple right-hand sides (MNNLS) arise in models that rely on additive linear combinations.
In particular, they are at the core of most nonnegative matrix factorization algorithms and have many applications.
The nonnegativity constraint is known to naturally favor sparsity, that is, solutions with few non-zero entries.
However, it is often useful to further enhance this sparsity, as it improves the interpretability of the results and helps reducing noise,
which leads to the sparse MNNLS problem.
In this paper, as opposed to most previous works that enforce sparsity column- or row-wise, we first introduce a novel formulation for sparse MNNLS,
with a matrix-wise sparsity constraint.
Then, we present a two-step algorithm to tackle this problem.
The first step divides sparse MNNLS in subproblems, one per column of the original problem.
It then uses different algorithms to produce, either exactly or approximately, a Pareto front for each subproblem, that is,
to produce a set of solutions representing different tradeoffs between reconstruction error and sparsity.
The second step selects solutions among these Pareto fronts in order to build a sparsity-constrained matrix that minimizes the reconstruction error.
We perform experiments on facial and hyperspectral images, and we show that our proposed two-step approach provides more accurate results
than state-of-the-art sparse coding heuristics applied both column-wise and globally.


###### References

Exact Biobjective k-Sparse Nonnegative Least Squares. N Nadisic, A Vandaele, N Gillis, JE Cohen. In EUSIPCO 2021.

Matrix-wise L0-constrained Sparse Nonnegative Least Squares. N Nadisic, JE Cohen, A Vandaele, N Gillis. In Machine Learning (Springer). 2022.


###### Biography

Nicolas Nadisic received the Diplôme d'Ingénieur (MSc degree) in Computer Science from INSA Lyon, France, in 2018.
He completed his PhD in 2022, in the department of Mathematics and Operational Research of the University of Mons, Belgium.
His is currently a postdoctoral researcher at the department of Telecommunications and Information Processing of Ghent University, Belgium.
His research interests include machine learning, signal processing, optimization, and data mining, with a particular focus on low-rank models,
sparse approximation, and blind source separation. 
