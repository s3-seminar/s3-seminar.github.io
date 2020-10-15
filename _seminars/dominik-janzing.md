---
title: Detecting confounding in multivariate linear models via spectral analysis
speaker: Dominik Janzing
affiliation: Max Planck Institute for Intelligent Systems
date: 2017-01-31 10:30
location: Salle du conseil du L2S
perso: http://is.tuebingen.mpg.de/person/janzing
aside: true
---

###### Abstract
We study a model where one target variable Y is correlated with a
vector X:=(X_1,...,X_d) of predictor variables being potential causes
of Y. We describe a method that infers to what extent the statistical
dependences between X and Y are due to the influence of X on Y and to
what extent due to a hidden common cause (confounder) of X and Y. The
method is based on an independence assumption stating that, in the
absence of confounding, the vector of regression coefficients
describing the influence of each X on Y has 'generic orientation'
relative to the eigenspaces of the covariance matrix of X. For the
special case of a scalar confounder we show that confounding typically
spoils this generic orientation in a characteristic way that can be
used to quantitatively estimate the amount of confounding. I also show
some encouraging experiments with real data, but the method is work in
progress and critical comments are highly appreciated. Postulating
'generic orientation' is inspired by a more general postulate stating
that P(cause) and P(effect|cause) are independent objects of Nature
and therefore don't contain information about each other [1,2,3], an
idea that inspired several causal inference methods already, e.g.
[4,5]. [1] Janzing, Schoelkopf: Causal inference using the algorithmic
Markov condition, IEEE TIT 2010. [2] Lemeire, Janzing: Replacing
causal faithfulness with the algorithmic independence of conditionals,
Minds and Machines, 2012. [3] Schoelkopf et al: On causal and
anticausal learning, ICML 2012. [4] Janzing et al: Telling cause frome
effect based on high-dimensional observations, ICML 2010. [5]
Shajarisales et al: Telling cause from effect in deterministic linear
dynamical systems, ICML 2015.