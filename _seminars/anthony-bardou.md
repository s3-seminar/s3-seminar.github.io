---
title: "Symmetry-Aware Bayesian Optimization via Max Kernels"
speaker: Anthony Bardou
affiliation: INDY Lab, EPFL
date: 2026-11-27 14:00
perso: https://abardou.github.io/
location: TBD
hybrid: https://teams.microsoft.com/meet/3918398331533368?p=lLA9iJiBqs2K3e0CYp
speakerdeck: 
aside: true
---


###### Abstract
Bayesian optimization (BO) is a powerful framework for optimizing noisy, expensive-to-evaluate black-box functions.
When the objective is invariant under a known group of actions, each evaluation reveals its value on a whole orbit of inputs,
and exploiting this symmetry can substantially improve sample efficiency. The standard approach averages a base kernel over the group (average kernel).
Alternatively, keeping the maximum similarity across orbits has long been considered in other domains,
but the resulting kernel (max kernel) is not positive semidefinite (PSD) in general,
which has prevented its use in BO. This talk revisits this idea through a PSD projection of the max kernel, extended to new points with the Nyström method.
Compared to existing invariant and non-invariant kernels, the resulting kernel achieves significantly lower regret on synthetic and real-world benchmarks,
with gains that grow with the size of the group, at no extra asymptotic cost.
This good performance is not explained by standard eigendecay arguments in the literature, which give a tighter regret bound for the average kernel.
I will resolve this tension through geometry: the two kernels place the same base prior in two very different spaces.
