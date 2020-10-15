---
title: Stochastic Quasi-Newton Langevin Monte Carlo
speaker: Umut Şimşekli
affiliation: LTCI, Télécom ParisTech
date: 2017-02-10 10:30
location: Salle du conseil du L2S
perso: http://perso.telecom-paristech.fr/~simsekli/
aside: true
---

###### Abstract
Recently, Stochastic Gradient Markov Chain Monte Carlo (SG-MCMC)
methods have been proposed for scaling up Monte Carlo computations to
large data problems. Whilst these approaches have proven useful in
many applications, vanilla SG-MCMC might suffer from poor mixing rates
when random variables exhibit strong couplings under the target
densities or big scale differences. In this talk, I will present a
novel SG-MCMC method that takes the local geometry into account by
using ideas from Quasi-Newton optimization methods. These second order
methods directly approximate the inverse Hessian by using a limited
history of samples and their gradients. Our method uses dense
approximations of the inverse Hessian while keeping the time and
memory complexities linear with the dimension of the problem. I will
provide formal theoretical analysis where it is shown that the
proposed method is asymptotically unbiased and consistent with the
posterior expectations. I will finally illustrate the effectiveness of
the approach on both synthetic and real datasets. This is a joint work
with Roland Badeau, Taylan Cemgil and Gaël Richard. arXiv:
https://arxiv.org/abs/1602.03442