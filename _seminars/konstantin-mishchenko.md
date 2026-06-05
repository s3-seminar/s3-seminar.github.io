---
title: "Atlas: Adaptive Stepsizes from First Principles"
speaker: Konstantin Mishchenko
affiliation: Meta
date: 2026-06-05 14:00
perso: https://www.konstmish.com/
location: Salle G. Hopper 0336, IBM
hybrid: https://teams.microsoft.com/meet/34597841354366?p=gdpTZHmimmhIzAkPh1
speakerdeck: 
aside: true
---


###### Abstract
In this presentation, we will discuss Atlas, an adaptive gradient method built from two principles.
First, an AdaGrad-inspired weighted estimate of past gradients lets the method estimate local smoothness,
which is essential for linear convergence on smooth objectives.
Second, a safeguard inspired by normalized gradient descent controls the per-step error,
giving guarantees that hold on unbounded domains and do not depend on the initial gradient,
unlike standard AdaGrad analyses.
The two ingredients combine into a single rule that we prove to converge,
in both deterministic and stochastic settings, on smooth and non-smooth convex problems as well as
smooth nonconvex objectives.
In addition, we design a momentum variant to provably limit the bias of the adaptive estimate in the
stochastic setting, and prove its nonconvex convergence as well.
We derive both scalar and coordinate-wise stepsizes,
showing theoretically the advantage of the latter under $\ell_{\infty}$ geometry.
We test the method empirically on convex problems and deep network training with models scaling up to
8 billion parameters, verifying that Atlas matches the empirical performance of Adam.
