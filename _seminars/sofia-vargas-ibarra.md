---
title: "Imagerie du thrombus avec l’IA pour la stratification des patients AVC"
speaker: Sofia Vargas Ibarra
affiliation: Univ. Paris Saclay, CNRS, CentraleSupélec, L2S
date: 2025-10-17 11:00
perso: 
location: new L2S location (IBM building), Room Hopper (Third floor)
hybrid: https://teams.microsoft.com/meet/388216564192?p=vAzXhmCUkFxCqZ1cUQ
aside: true
---


<div style="text-align:center">
<script defer class="speakerdeck-embed" data-id="22e33795804c45459fa999854cb3ca1d" data-ratio="1.33333333333333" src="//speakerdeck.com/assets/embed.js"></script>
</div>


###### Abstract
L’AVC est responsable d’environ 6 millions de décès chaque année.
Sa prise en charge médicale est coûteuse et prend du temps, car elle repose sur l’interprétation des scanners cérébraux par des experts.
Le thrombus, étant un caillot sanguin, provoque une interruption du flux sanguin lors des AVC ischémiques, provoquant des lésions cérébrales.
Nous proposons un pipeline complet pour la prise en charge des patients victimes d’AVC.
Nous segmentons la lésion à l’aide de nnUnet et le thrombus grâce à notre architecture proposée (UpAttLLSTM), qui fusionne les modalités informatives du thrombus et de la lésion.
Afin de généraliser cette approche à plusieurs appareils, où certaines modalités pourraient être manquantes, nous proposons une suppression progressive des modalités,
permettant une segmentation dans plusieurs scénarios, même en l’absence d’une modalité d’image.
Enfin, en utilisant l’architecture de segmentation des lésions, qui aboutit à un score Dice d’environ 0,78, et celle du thrombus,
qui obtient un score Dice de 0,65 lorsque toutes les modalités sont présentes, nous extrayons des caractéristiques de texture, d’intensité et de forme afin de prédire le succès du traitement.
En utilisant toutes les modalités et les masques de segmentation, le succès de la thrombolyse est prédit avec une précision de 76%.
Ce pipeline complet fournit des informations utiles aux neurologues et aux médecins non experts pour la prise en charge des patients victimes d’un AVC ischémique et le choix du traitement.


