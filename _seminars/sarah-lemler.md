---
title: Estimation de l’intensité d’un processus de comptage en grande dimensionessus de comptage en grande dimension
speaker: Sarah Lemler
affiliation: MICS, CentraleSupélec, Gif
date: 2017-11-17 14:00
location: Salle du conseil du L2S
perso: None
aside: true
---

###### Abstract
Nous cherchons à estimer/apprendre le lien entre des covariables en
grande dimension et l’intensité avec laquelle des événements se
produisent (décès, crises d’asthme, achats, notes de blogs,
sinistres...). Pour répondre à cette problématique, nous proposons
deux approches pour estimer l’intensité de sauts d’un processus de
comptage en présence d’un grand nombre de covariables. D’abord, nous
considérons une intensité non-paramétrique et nous l’estimons par le
meilleur modèle de Cox. Nous considérons alors une procédure Lasso,
spécifique à la grande dimension, pour estimer simultanément les deux
paramètres inconnus du meilleur modèle de Cox approximant l’intensité.
Nous prouvons des inégalités oracles non-asymptotiques pour
l’estimateur Lasso obtenu. Dans une seconde partie, nous supposons que
l’intensité satisfait un modèle de Cox. Nous proposons deux procédures
en deux étapes pour estimer les paramètres inconnus du modèle de Cox.
La première étape est commune aux deux procédures, il s’agit d’estimer
le paramètre de régression en grande dimension via une procédure
Lasso. Le risque de base est ensuite estimé soit par sélection de
modèles, soit par un estimateur à noyau avec une fenêtre choisie par
la méthode de Goldenshluger et Lepski. Nous établissons des inégalités
oracles non-asymptotiques pour les deux estimateurs du risque de base
ainsi obtenus. Nous menons une étude comparative de ces estimateurs
sur des données simulées, et enfin, nous appliquons les procédures
implémentées à une base de données sur le cancer du sein.