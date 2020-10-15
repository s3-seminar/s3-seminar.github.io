---
title: High dimensional sampling with the Unadjusted Langevin Algorithm
speaker: Alain Durmus
affiliation: LTCI, Telecom ParisTech
date: 2016-11-23 10:30
location: Salle du conseil du L2S
perso: https://perso.telecom-paristech.fr/~durmus/
speakerdeck: https://speakerdeck.com/s3_seminar/alain-durmus
aside: true
---

###### Abstract
Recently, the problem of designing MCMC sampler adapted to high-
dimensional distributions and with sensible theoretical guarantees has
received a lot of interest. The applications are numerous, including
large-scale inference in machine learning, Bayesian nonparametrics,
Bayesian inverse problem, aggregation of experts among others. When
the density is L-smooth (the log-density is continuously
differentiable and its derivative is Lipshitz), we will advocate the
use of a “rejection- free” algorithm, based on the discretization of
the Euler diffusion with either constant or decreasing stepsizes. We
will present several new results allowing convergence to stationarity
under different conditions for the log-density (from the weakest,
bounded oscillations on a compact set and super-exponential in the
tails to the log concave). When the density is strongly log-concave,
the convergence of an appropriately weighted empirical measure is also
investigated and bounds for the mean square error and exponential
deviation inequality for Lipschitz functions will be reported.
Finally, based on optimzation techniques we will propose new methods
to sample from high dimensional distributions. In particular, we will
be interested in densities which are not continuously differentiable.
Some Monte Carlo experiments will be presented to support our
findings.