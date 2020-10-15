---
title: Analysis of remote sensing multi-sensor heterogeneous images
speaker: Jorge Prendes
affiliation: IRIT, University of Toulouse and SONDRA, CentraleSupelec, FR
date: 2015-03-20 10:30
location: None
perso: None
speakerdeck: https://speakerdeck.com/s3_seminar/jorge-prendes
aside: true
---

###### Abstract
Remote sensing images are images of the Earth acquired from planes or
satellites. In recent years the technology enabling this kind of
images has been evolving really fast. Many different sensors have been
developed to measure different properties of the earth surface,
including optical images, SAR images and hyperspectral images. One of
the interest of this images is the detection of changes on datasets of
multitemporal images. Change detection has been thoroughly studied on
the case where the dataset consist of images acquired by the same
sensor. However, having to deal with datasets containing images
acquired from different sensors (heterogeneous images) is becoming
very common nowadays. In order to deal with heterogeneous images, we
proposed a statistical model which describe the joint distribution of
the pixel intensity of the images, more precisely a mixture model. On
unchanged areas, we expect the parameter vector of the model to belong
to a manifold related to the physical properties of the objects
present on the image, while on areas presenting changes this
constraint is relaxed. The distance of the model parameter to the
manifold can be thus be used as a similarity measure, and the manifold
can be learned using ground truth images where no changes are present.
The model parameters are estimated through a collapsed Gibbs sampler
using a Bayesian non parametric approach combined with a Markov random
field. In this talk I will present the proposed statistical model, its
parameter estimation, and the manifold learning approach. The results
obtained with this method will be compared with those of other
classical similarity measures.

###### Biography
Jorge Prendes was born in Santa Fe, Argentina in 1987. He received the
5 years Eng. degree in Electronics Engineering with honours from the
Buenos Aires Institute of Technology (ITBA), Buenos Aires, Argentina
in July 2010. He worked on Signal Processing at ITBA within the
Applied Digital Electronics Group (GEDA) from July 2010 to September
2012. Currently he is a Ph.D. student in Signal Processing in SONDRA
laboratory at Supélec, within the cooperative laboratory TéSA and the
Signal and Communication Group of the Institut de Recherche en
Informatique de Toulouse (IRIT). His main research interest include
image processing, applied mathematics and pattern recognition.