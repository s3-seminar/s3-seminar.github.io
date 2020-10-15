---
title: Inversion de données en traitement du signal et des images - régularisation parcimonieuse et algorithmes de minimisation L0
speaker: Charles Soussen
affiliation: Centre de Recherche en Automatique de Nancy (CRAN, UMR CNRS 7039), Université de Lorraine
date: 2017-05-23 14:00
location: Salle du conseil du L2S
perso: http://w3.cran.univ-lorraine.fr/perso/charles.soussen/
aside: true
---

###### Abstract
Dans la première partie de l'exposé, je présenterai différents
problèmes inverses auxquels je me suis intéressé ces dernières années
et les contextes applicatifs associés : reconstruction d'images en
tomographie, analyse d'images biologiques et d'images hyperspectrales
en microscopie, problèmes d'inversion de données en spectroscopie
optique avec applications biomédicales. Lorsque les données
disponibles sont en nombre limité et partiellement informatives sur la
quantité à estimer (problèmes inverses mal posés), la prise en compte
d’informations a priori sur les inconnues est indispensable, et
s’effectue par le biais des techniques de régularisation. Dans la
seconde partie de l'exposé, je présenterai plus particulièrement la
régularisation parcimonieuse de problèmes inverses, basée sur la
minimisation de la "norme" l0. Les algorithmes heuristiques proposés
sont conçus pour minimiser des critères mixtes L2-L0 du type min_x
J(x;lambda) = || y - Ax ||_2^2 + lambda || x ||_0. Ce problème
d'optimisation est connu pour être fortement non-convexe et NP-
difficile. Les heuristiques proposées (appelées algorithmes
"gloutons") sont définies en tant qu'extensions d'Orthogonal Least
Squares (OLS). Leur développement est motivé par le très bon
comportement empirique d'OLS et de ses versions dérivées lorsque la
matrice A est mal conditionnée. Je présenterai deux types
d'algorithmes pour minimiser J(x;lambda) à lambda fixé et pour un
continuum de valeurs de lambda. Finalement, je présenterai quelques
résultats théoriques visant à garantir que les algorithmes gloutons
permettent de reconstruire exactement le support d'une représentation
parcimonieuse y = Ax*, c'est-à-dire le support du vecteur x*.

###### Biography
Charles Soussen est né en France en 1972. Il est diplômé de l'Ecole
Nationale Supérieure en Informatique et Mathématiques Appliquées,
Grenoble (ENSIMAG) en 1996. Il a obtenu sa thèse en traitement du
signal et des images au Laboratoire des Signaux et Systèmes (L2S),
Université de Paris-Sud, Orsay, en 2000, et son Habilitation à Diriger
des Recherches à l'Université de Lorraine en 2013. Il est actuellement
Maître de Conférences à l'Université de Lorraine, et au Centre de
Recherche en Automatique de Nancy depuis 2005. Ses thématiques de
recherche concernent les problèmes inverses et l'approximation
parcimonieuse.