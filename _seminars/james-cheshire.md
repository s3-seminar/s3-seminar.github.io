---
title: "Active Seriation: Efficient Ordering Recovery with Statistical Guarantees"
speaker: James Cheshire
affiliation: LTCI, Telecom Paris
date: 2026-03-27 11:00
perso: https://sites.google.com/view/jamescheshireresearch/home
location: Salle G. Hopper 0336, IBM
hybrid: https://teams.microsoft.com/meet/3353104168864?p=utH2t3EZIb9dXOyKJl 
speakerdeck: 
aside: true
---


###### Abstract
In seriation, the goal is to recover an unknown ordering of n items based on noisy observations of pairwise similarities.
The similarities are assumed to correlate with the underlying ordering: pairs of items that are close in the ordering tend to have higher similarity scores, and vice versa.
During this talk, we consider the problem of seriation in an active setting, that is, the learner sequentially selects which item pairs to query and receives noisy similarity measurements.
We will propose a novel active seriation algorithm, that is computationally efficient, while requiring minimal assumptions.
We demonstrate that our algorithm recovers the correct ordering with high probability and provide optimal performance guarantees regarding both the probability of error and the number of observations required for successful recovery.
Finally, we evaluate the performance of our approach, when used for RNA sequencing, on real data.

###### Bio
James is currently working in the LTCI lab of Telecom Paris, where he holds a Foundation Mathematique Jacques Hadamard postdoctoral fellowship.
Prior to Telecom Paris, James completed his PhD in mathematics while at the Otto von Guericke University and University of Potsdam.
His research is primarily in learning theory with a focus on sequential learning problems.
In particular, he has explored several variations of the multi armed bandit and sequential problems in ranking and decision making.
