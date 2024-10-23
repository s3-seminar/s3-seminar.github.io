---
title: "Large-scale causal structure learning: challenges and new methods"
speaker: Shuyu Dong
affiliation: Université Paris-Saclay and INRIA Saclay
date: 2024-11-29 11:00
perso: https://shuyu-d.github.io/
location: new L2S location (IBM building), Room Bur 2.1 (Second floor)
hybrid: https://teams.microsoft.com/l/meetup-join/19:178a6f926336444088eb120e42476f36@thread.tacv2/1727244372227?context=%7B%22Tid%22:%2261f3e3b8-9b52-433a-a4eb-c67334ce54d5%22,%22Oid%22:%224d6c63a8-7eae-4099-804e-68bcb968bec0%22%7D
youtube: 
speakerdeck: 
aside: true
---

###### Abstract
Learning causal structures from observational data is a fundamental problem.
In the context of linear structural equation models (SEMs), I will present our works in addressing the computational challenges in the causal structure learning problem.
The first work [1] considers a more basic question than causal structure learning, which is about how to learn a directed acyclic graph (DAG)
that is closest to a weighted adjacency matrix of a directed graph. We proposed a low-rank matrix model of DAGs combining low-rank matrix factorization
with a sparsification mechanism, and the model is learned through a continuous optimization method.
The second work [2] is about a divide-and-conquer strategy (called DCILP) for causal structure learning.
The divide phase proceeds by identifying the Markov blanket MB($X_i$) of each variable $X_i$, and independently addressing the subproblems restricted to each MB.
The novelty of DCILP lies in the conquer phase, which tackles the problem of aggregating the local causal graphs from the divide phase.
Such an aggregation is a challenging combinatorial optimization problem especially in large-scale applications.
We show that this reconciliation can be formulated as an integer linear programming (ILP) problem that is delegated to an ILP solver,
and that the resulting algorithm demonstrates significant improvements in scalability with satisficatory learning accuracy.


###### References
[1] Shuyu Dong and Michele Sebag. From graphs to DAGs: a low-complexity model and a scalable algorithm. In Joint European Conference on Machine Learning and Knowledge Discovery in Databases, pages 107--122. Springer, 2022.

[2] Shuyu Dong, Michele Sebag, Kento Uemura, Akito Fujii, Shuang Chang, Yusuke Koyanagi, and Koji Maruhashi. DCDILP: a distributed learning method for large-scale causal structure learning, 2024. URL https://arxiv.org/abs/2406.10481.



###### Bio
My main reserach area is optimization for machine learning and causal learning.
I have worked on Riemannian optimization methods for learning low-rank matrix and tensor decomposition models,
with applications in matrix and tensor completion (on recommendation data, traffic and visual data).
One of the topics I focus on is about Riemannian preconditioning and convergence properties of the underlying Riemannian gradient descent algorithms.
I am currently working on topics in the intersection of causal learning and optimization such as matrix decomposition for DAG learning and integer programming methods.
The main outcome of this research is the development of scalable algorithms for learning large causal graphs from observational data.
