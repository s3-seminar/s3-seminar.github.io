---
title: Efficient MCMC sampling via asymptotically exact data augmentation
speaker: Maxime Vono
affiliation: "IRIT — INP-ENSEEIHT"
perso: "https://mvono.github.io"
date: 2020-12-11 14:00
feature_image: "maxime-vono.jpg"
image: "maxime-vono.jpg"
online: "https://eu.bbcollab.com/guest/453cb1d5e71b4aa194bbf6405eb730f1"
aside: true
---

###### Abstract
Performing exact Bayesian inference for complex models is computationally intractable. Markov chain Monte Carlo (MCMC) algorithms can provide reliable approximations of the posterior distribution but are expensive for large datasets and high-dimensional models. A standard approach to mitigate this complexity consists in using subsampling techniques or distributing the data across a cluster. However, these approaches are typically unreliable in high-dimensional scenarios. We focus here on an alternative MCMC scheme, coined Split Gibbs Sampler (SGS), exploiting a splitting strategy akin to the one used by quadratic penalty approaches in optimisation. This MCMC algorithm targets an approximation of a given posterior distribution which comes from an approximate statistical framework called Asymptotically Exact Data Augmentation (AXDA). Under standard regularity conditions, we quantitatively assess the bias associated to AXDA, establish explicit convergence rates for SGS and provide practitioners with explicit guidelines to fix the number of SGS steps. We finally support our methodology with numerical illustrations on challenging Bayesian inference problems.

###### References 
[1] Maxime Vono, Nicolas Dobigeon, and Pierre Chainais, *High-dimensional Gaussian sampling: A review and a unifying approach based on a stochastic proximal point algorithm.* arXiv: 2010.01510.

[2] Maxime Vono, Daniel Paulin, and Arnaud Doucet, *Efficient MCMC sampling with dimension-free convergence rate using ADMM-type splitting*. arXiv: 1905.11937.

[3] Maxime Vono, Nicolas Dobigeon, and Pierre Chainais (2020), *Asymptotically exact data augmentation: models, properties and algorithms*, Journal of Computational and Graphical Statistics (in press).

[4] Maxime Vono, Nicolas Dobigeon, and Pierre Chainais (2019). *Split-and-augmented Gibbs sampler - Application to large-scale inference problems*, IEEE Transactions on Signal Processing, vol. 67, no. 6, pp. 1648-1661.

###### Biography
Maxime Vono recently obtained his Ph.D. in statistics from the University of Toulouse where he was supervised by Nicolas Dobigeon (IRIT, INP-ENSEEIHT) and Pierre Chainais (CRIStAL, Centrale Lille). In spring 2019, he was a visiting research scholar at the Department of Statistics of the University of Oxford working with Arnaud Doucet (Oxford & Deepmind). Prior to that, he both graduated in 2017 from Ecole Centrale de Lille majoring in data sciences and University of Lille majoring in probability and statistics. He is affiliated to the ORION-B project which gathers astrophysicists, data scientists and statisticians in order to better understand the formation of stars in our universe. His research interests lie in Bayesian modelling, the development of efficient computational methods for inferring unknown objects in complex problems and their applications to signal/image processing and machine learning.
