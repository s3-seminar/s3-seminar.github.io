---
title: "Variational Inference with Mixtures of Gaussians"
speaker: Anna Korba
affiliation: ENSAE, IP Paris
date: 2026-05-22 14:00
perso: https://akorba.github.io/
location: Salle G. Hopper 0336, IBM
hybrid: https://teams.microsoft.com/meet/34597841354366?p=gdpTZHmimmhIzAkPh1
speakerdeck: 
aside: true
---


###### Abstract
Variational inference (VI) is a popular approach in Bayesian inference,
that looks for the best approximation of the posterior distribution within a parametric family,
minimizing a loss that is typically the (reverse) Kullback-Leibler (KL) divergence.
In this paper, we focus on the following parametric family: mixtures of isotropic Gaussians
(i.e., with diagonal covariance matrices proportional to the identity) and uniform weights.
We develop a variational framework and provide efficient algorithms suited for this family.
In contrast with mixtures of Gaussian with generic covariance matrices,
this choice presents a balance between accurate approximations of multimodal Bayesian posteriors,
while being memory and computationally efficient.
Our algorithms implement gradient descent on the location of the mixture components
(the modes of the Gaussians), and either (an entropic) Mirror or Bures descent on their variance parameters.
We illustrate the performance of our algorithms on numerical experiments.
