---
title: Segmentation-déconvolution d'images texturées - gestion des incertitudes par une approche bayésienne hiérarchique et un échantillonnage stochastique
speaker: Jean-François Giovannelli
affiliation: Prof. à l'université de Bordeaux (IMS Lab)
date: 2019-07-09 16:30
location: Amphitéatre Janet (bât. Breguet)
perso: None
speakerdeck: https://speakerdeck.com/s3_seminar/jean-francois-giovannelli
aside: true
---

###### Abstract
La présentation concerne la déconvolution-segmentation conjointe pour des images
présentant des texturées orientées. Les images sont constituées de régions
présentant des patchs de textures appartenant à un ensemble de K classes
prédéfinies. Chaque classe est modélisée par un champ gaussien piloté par une
densité spectrale de puissance paramétrique de paramètres inconnus. Par
ailleurs, les labels de classes sont modélisés par un champ de Potts de
paramètre est également inconnu. La méthode repose sur une description
hiérarchique et une stratégie d'estimation conjointement des labels, des K
images texturées, ainsi que des hyperparamètres: niveaux du bruit et des images
ainsi que paramètres de texture et du champ de Potts. La stratégie permet de
définir des estimateurs optimaux au sens d'un risque joint: maximiseur ou
moyenne a posteriori selon les paramètres. Ils sont évalués numériquement à
partir d'échantillons de loi a posteriori, eux-mêmes obtenus par un algorithme
de Gibbs par bloc. Deux des étapes sont délicates: (1) le tirage des images
texturées, gaussiennes de grande dimension, est réalisé par un algorithme de
Perturbation-Optimization [a] et (2) le tirage des paramètres des images
texturées obtenu par une étape de Fisher Metropolis-Hastings [b]. On donnera
plusieurs illustrations numériques notamment en terme de quantification des
incertitudes. Le travail est publié dans [c].

[a] F. Orieux, O. Féron and J.-F. Giovannelli, "Sampling high- dimensional
Gaussian distributions for general linear inverse problems", Signal Processing
Letters, May 2012.

[b] C. Vacar, J.-F. Giovannelli, Y. Berthoumieu, "Langevin and Hessian with
Fisher approximation stochastic sampling for parameter estimation of structured
covariance" ICASSP 2011.

[b'] M. Girolami, B. Calderhead, "Riemannian manifold Hamiltonian Monte Carlo",
Journal of the Royal Statistical Society, 2011.

[c] C. Vacar and J.-F. Giovannelli, "Unsupervised joint deconvolution and
segmentation method for textured images: A Bayesian approach and an advanced
sampling algorithm", EURASIP Journal on Advances in Signal Processing, 2019

###### Biography
Jean-François Giovannelli was born in Beziers, France, in 1966. He received the
Dipl. Ing. degree from the Ecole Nationale Supérieure de l'Electronique et de
ses Applications, Cergy, France, in 1990, and the Ph.D. degree and the H.D.R.
degree in signal-image processing from the Universite Paris-Sud, Orsay, France,
in 1995 and 2005, respectively. From 1997 to 2008, he was an Assistant Professor
with the Universite Paris-Sud and a Researcher with the Laboratoire des Signaux
et Systemes, Groupe Problèmes Inverses. He is currently a Professor with the
Universite de Bordeaux, France and a Researcher with the Laboratoire de
l'Integration du Matériau au Système, Groupe Signal- Image, France. His research
focuses on inverse problems in signal and image processing, mainly unsupervised
and myopic problems. From a methodological standpoint, the developed
regularization methods are both deterministic (penalty, constraints,...) and
Bayesian. Regarding the numerical algorithms, the work relies on optimization
and stochastic sampling. His application fields essentially concern
astronomical, medical, proteomics, radars and geophysical imaging.
