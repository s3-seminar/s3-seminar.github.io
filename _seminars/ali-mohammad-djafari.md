---
title: Inverse problems in signal and image processing and Bayesian inference framework- from basic to advanced Bayesian computation
speaker: Ali Mohammad-Djafari
affiliation: CNRS, L2S, FR
date: 2015-03-27 10:30
location: None
perso: http://djafari.free.fr/index.htm
speakerdeck: https://speakerdeck.com/s3_seminar/ali-mohammad-djafari
aside: true
---

###### Abstract
In signal and image processing community, we can distinguish two
categories: - Those who start from the observed signals and images and
do classical processing: filtering for denoising, change detection,
contour detection, segmentation, compression, … - The second category
called “model based”, before doing any processing try first to
understand from where those signals and images come from and why they
are here . So, first defining what quantity has been at the origin of
those observations, then modeling their link by “forward modeling” and
finally doing inversion. This approach is often called “Inverse
problem approach”. Then, noting the “ill-posedness” of the inverse
problems, many “Regularization methods” have been proposed and applied
successfully. However, deterministic regularization has a few
limitations and recently the Bayesian inference approach has become
the main approach for proposing unsupervised methods and effective
solutions in many real applications. Interestingly, even many
classical methods have found better understanding when re-stated as
inverse problem. The Bayesian approach with simple prior models such
as Gaussian, Generalized Gaussian, Sparsity enforcing priors or more
sophisticated Hierarchical models such as Mixture models, Gaussian
Scale Mixture or Gauss-Markov-Potts models have been proposed in
different applications of imaging systems with great success. However,
Bayesian computation still is too costly and need more practical
algorithms than MCMC. Variational Bayesian Approximation (VBA) methods
have recently became a standard for computing the posterior means in
unsupervized methods. Interestingly, we show that VBA includes Joint
Maximum A Posteriori (JMAP) and Expectation-Maximization (EM) as
special cases. VBA is much faster than MCMC methods, but, it gives
only access to the posterior means. This talk gives an overview of
these methods with examples in Deconvolution (simple or blind, signal
or image) and in Computed Tomography (CT).