---
title: "Filling the gaps: a story of priors and conditional probabilities"
speaker: Thomas Moreau
affiliation: Parietal - Inria Saclay
date: 2024-01-19 11:00
perso: https://tommoral.github.io
location: Salle G. Hopper 0336, IBM
hybrid: https://teams.microsoft.com/meet/32287243237206?p=pgTms3rsDJ5B3hJ3Hu
speakerdeck: 
aside: true
---


###### Abstract
Inverse problems are often ill-posed: incomplete measurements, noise, and ambiguity mean that we must rely on priors to reconstruct meaningful solutions.
In the first part of this talk, I will present recent work that analyzes the limitations and challenges of these approaches when solving
unsupervised inverse problems—how the choice of priors can bias reconstructions, how conditional models interact with measurement operators,
and what this reveals about the fundamental difficulty of filling in missing information.

Building on this perspective, I will then introduce FIRE (Fixed point Restoration),
a framework that addresses these challenges by defining implicit priors not just through denoisers but through general restoration models.
The key idea is to characterize natural signals as fixed points of a degradation–restoration cycle,
enabling a principled and flexible way to integrate pretrained networks into inverse problem solvers.
This fixed-point view not only broadens the class of usable priors but also leads to robust, algorithms with strong empirical performance.

