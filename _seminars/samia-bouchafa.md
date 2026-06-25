---
title: "Vision multimodale dynamique en environnements dégradés"
speaker: Samia Bouchafa-Bruneau
affiliation: Université Évry Paris-Saclay, Laboratoire IBISC
date: 2026-06-26 11:00
perso: https://cv.hal.science/samia-bouchafa
location: Salle G. Hopper 0336, IBM
hybrid: https://teams.microsoft.com/meet/34597841354366?p=gdpTZHmimmhIzAkPh1
speakerdeck: 
aside: true
---


###### Abstract
La problématique centrale des travaux présentés est la suivante : comment estimer de manière robuste l'état
d'un agent mobile - sa pose, son ego-mouvement, la structure de la scène - lorsque les capteurs de vision sont
hétérogènes et que les conditions d'acquisition sont dégradées ? Dans un contexte applicatif contraint, ces
travaux s'appuient sur un paradigme dit de « vision opportuniste » : une approche orientée tâche, tirant parti
des connaissances a priori propres à l'application ainsi que des indices disponibles dans la scène, afin de
déployer les seuls opérateurs de vision strictement nécessaires à l'accomplissement de cette tâche. Ce fil
conducteur structure un programme de recherche décliné en trois familles de capteurs non conventionnels,
chacune soulevant des verrous spécifiques sur les plans de la représentation des données, de l'estimation et de
la fusion.

Un premier axe porte sur les caméras événementielles, dont la nature asynchrone et à haute résolution
temporelle rompt avec les paradigmes classiques du traitement d'images. Contrairement aux caméras
conventionnelles, ces capteurs neuromorphiques permettent à chaque pixel de fournir des informations de
manière indépendante et asynchrone dès qu'un changement de luminosité est détecté, éliminant les artefacts
de flou cinétique et offrant une plage dynamique élevée. Le verrou fondamental est que les algorithmes
classiques (flot optique, estimation de pose, SLAM) ne sont pas directement applicables à ces flux d'événements
asynchrones. Nous avons abordé ce défi en développant un système d'odométrie visuo-inertielle pour caméras
événementielles. Nous avons poursuivi les travaux par l'estimation de pose 6DOF par apprentissage profond.
Un travail en cours explore la piste des réseaux de neurones impulsionnels (SNN) pour guider l'estimation du
flot optique événementiel par des filtres sélectifs directionnels, poussant vers une cohérence bio-inspirée entre
le capteur et l'algorithme de traitement.

Un deuxième axe porte sur la fusion de capteurs hétérogènes pour le SLAM multimodal. Les travaux se sont
attachés à traiter la fusion de flux synchrones et asynchrones issus de capteurs de nature différente. La méthode
DH-PTAM combine les forces de capteurs visuels hétérogènes (caméras stéréo événementielles et caméras
synchrones) dans un cadre de référence unifié via une approche originale de synchronisation spatio-temporelle,
couplée à un apprentissage profond pour l'extraction et la description de primitives robustes.

Un troisième axe porte sur la fusion multimodale par apprentissage profond pour l'analyse de scènes
extérieures en conditions difficiles. Les travaux se sont focalisés sur l'utilisation conjointe de données visuelles
multimodales (images couleur, images infrarouges et images de profondeur) pour améliorer la précision et la
robustesse de l'analyse de scènes, avec notamment des contributions sur l'adaptation de domaine non
supervisée guidée par des indices de profondeur pour apprendre des représentations invariantes au domaine.

Les verrous transversaux qui structurent ces travaux sont au nombre de trois : (1) une représentation unifiée
de flux hétérogènes (synchrones/asynchrones, visibles/infrarouges/SWIR, perspectives/omnidirectionnels)
dans un espace commun permettant leur exploitation conjointe ; (2) une robustesse aux dégradations
(variations d'éclairage, occultations, mouvements rapides, transitions indoor/outdoor) sans recalibration ni
réapprentissage systématique ; (3) une généricité des estimateurs, capables de maintenir leurs performances
face à des changements de modalité ou de contexte applicatif. Ces trois verrous définissent les axes privilégiés
de collaboration, aussi bien sur les fondements méthodologiques (représentations événementielles, fusion
multimodale, décision robuste) que sur les plateformes expérimentales (traitement de séquences d’images,
vision dynamique, perception embarquée).
