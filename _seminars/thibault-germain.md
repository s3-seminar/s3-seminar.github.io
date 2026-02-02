---
title: "Comparing dynamical systems with operator learning and optimal transport"
speaker: Thibault Germain
affiliation: CMAP, Polytechnique
date: 2026-03-13 11:00
perso: https://thibaut-germain.github.io/
location: Salle G. Hopper 0336, IBM
hybrid: https://teams.microsoft.com/meet/39263954664012?p=YrzI7XwaXKj1aJ84v7
speakerdeck: 
aside: true
---


###### Abstract
The geometry of dynamical systems estimated from trajectory data is a major challenge for machine learning applications.
Koopman and transfer operators provide a linear representation of nonlinear dynamics through their spectral decomposition, offering a natural framework for comparison.
We propose a novel approach representing each system as a distribution of its joint operator eigenvalues and spectral projectors and defining a metric between systems leveraging optimal transport.
The proposed metric is invariant to the sampling frequency of trajectories.
It is also computationally efficient, supported by finite-sample convergence guarantees, and enables the computation of Fréchet means, providing interpolation between dynamical systems.
Experiments on simulated and real-world datasets show that our approach consistently outperforms standard operator-based distances in machine learning applications,
including dimensionality reduction and classification, and provides meaningful interpolation between dynamical systems.
