---
title: A Bayesian deep learning approach in thermal remote imaging with hyper-resolution
speaker: Ning Chu
affiliation: Institute of process equipment, College of Energy Engineering, Zhejiang University (Hangzhou, China)
date: 2019-07-09 10:30
location: Salle du conseil du L2S
perso: None
aside: true
---

###### Abstract
Remote monitoring and early warning of thermal source abnormality play
more and more important roles in fire prevention for the museums and
historical monuments (Notre dame de Paris e.g.), metro and electric
vehicle (Tesla e.g.) etc. However, conventional thermal imaging
techniques cannot obtain the accurate temperature distribution of
thermal sources in the far-fields. This is due to the fact that true
temperature of thermal sources, according to heat radiation model,
depends on many complex factors such as background temperature,
environment humidity and surface emissivity . To solve the above
challenge, we propose a Bayesian deep learning approach in thermal
remote imaging with hyper-resolution. And mixture Gaussian priors are
employed to model the temperature distribution of thermal sources, as
well as background temperature. Meanwhile, sparsity-enforcing prior of
temperature gradient is also utilized for spatial hyper-resolution.
Moreover, the environment humidity and surface emissivity in heat
radiation model can be studied by latent variables in Bayesian
Hierarchy Network, so that these two important parameters can be
estimated by maximizing the entropy of variational Bayesian inference.
Through this Bayesian deep learning framework (sampling-training-
updating), temperature mapping of hot sources can be accurately
obtained (about 0.5 degree Celsius variation) as far as 5-10 meters
way through a cost-effective infra-red camera (<100 Euros, 7 degree
Celsius variation ) . Even without knowing the exact environment
information, proposed approach is able to learn rapidly from remote
monitoring data about heat radiation parameters. Based on proposed
approach, a carry-on system of remote thermal imaging system has been
invented for monitor the abnormal heating in metro system in Guangzhou
city China.

###### Biography
Mr. Ning Chu received the Bachelor in information engineering from the
National University of Defense Technology in 2006. He obtain the
master and PhD in automatic signal, and image processing from the
University of Paris Sud, France in 2010 and 2014 respectively. He then
won the positions of scientific collaborator in École Polytechnique
Fédérale de Lausanne, Switzerland, and senior lecturer in Zhejiang
Unviersity. His research interests mainly focus on acoustic source
imaging, Bayesian deep learning in condition monitoring and inverse
problem applied in super resolution imaging. He has published more
than 22 peer-reveiwer journal papers, invited for lectures by top
international scientific conferences, own 5 China patents and 6
software copyrights.