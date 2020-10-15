---
title: Non-negative orthogonal greedy algorithms for sparse approximation
speaker: Thanh T. Nguyen
affiliation: CRAN, L2S
date: 2017-12-08 10:30
location: None
perso: None
aside: true
---

###### Abstract
Sparse approximation under non-negativity constraints naturally arises
in several applications. Many sparse solvers can be directly extended
to the non-negative setting. It is not the case of Orthogonal Matching
Pursuit (OMP), a well-known sparse solver, which gradually updates the
sparse solution support by selecting a new dictionary atom at each
iteration. When dealing with non-negative constraints, the orthogonal
projection computed at each OMP iteration is replaced by a non-
negative least-squares (NNLS) subproblem whose solution is not
explicit. Therefore, the usual recursive (fast) implementations of OMP
do not apply. A Non-negative version of OMP (NNOMP) was proposed in
the recent literature together with several variations. In my talk, I
will first recall the principle of greedy algorithms, in particular
NNOMP, and then, I will introduce our proposed improvements, based on
the use of the active-set algorithm to address the NNLS subproblems.
The structure of the active-set algorithm is indeed intrisically
greedy. Moreover, the active-set algorithm can be called with a warm
start, allowing us to fastly solve the NNLS subproblems. (Joint work
with Charles Soussen (L2S), Jérôme Idier (LS2N) and El-Hadi Djermoune
(CRAN).)