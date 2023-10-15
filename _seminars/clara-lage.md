---
title: "Sparse coding methods applied to DNA replication analysis"
speaker: Clara Lage
affiliation: ENS de Lyon, Physics laboratory
date: 2023-10-13 11:00
perso:
location: Salle des séminaires du L2S
hybrid: https://teams.microsoft.com/l/meetup-join/19%3a178a6f926336444088eb120e42476f36%40thread.tacv2/1695118538320?context=%7b%22Tid%22%3a%2261f3e3b8-9b52-433a-a4eb-c67334ce54d5%22%2c%22Oid%22%3a%224d6c63a8-7eae-4099-804e-68bcb968bec0%22%7d
youtube: 
speakerdeck: https://speakerdeck.com/s3_seminar/clara-lage
aside: true
---

<div style="text-align:center">
<script defer class="speakerdeck-embed" data-id="cc220856bbbc4fa3b31854f95ea0766f" data-ratio="1.33333333333333" src="//speakerdeck.com/assets/embed.js"></script>
</div>


###### Abstract

Cellular replication is widely studied using modern imaging methods.
This work aims to understand DNA replication at its most detailed level, which can not be achieved with microscopy images.
The data combines genetic sequencing and replication progress [1].
Our goal is to estimate important parameters such as the positions of replication origins in the DNA strand, speed of replication and direction.
We are going to discuss a time-scale dictionary approach with several sparse coding methods: LASSO, Matching Pursuit and Sliding Frank-Wolfe [2,4] (off-the-grid approach).
A hybrid method [3], that considers speed as a discrete parameter and position as continuous, will be presented and compared to others in the case of DNA replication.
We will also discuss other ways of approaching this problem by reformulating it as an inverse problem.

###### References

[1] B. Theulot et al. “Genome-wide mapping of individual replication fork velocities using nanopore sequencing”. In: Nature Communications 13 (2022). doi: 10.1038/s41467-022-31012-0.

[2] L. Blanc-Féraud B. Laville and G. Aubert. “Off-The-Grid Variational Sparse Spike Recovery: Methods and Algorithms”. In: Journal of Imaging 7.12 (2021). issn: 2313-433X. doi: 10 . 3390 / jimaging7120266. url: https://www.mdpi.com/2313-433X/7/12/266.

[3] Clara Lage et al. Time-Scale Hybrid Continuous-Discrete Sliding Frank-Wolfe Method. eprint: https://hal.science/hal-04146737/.

[4] G. Peyré Q. Denoyelle V. Duval and E. Soubies. “The sliding Frank–Wolfe algorithm and its application to super-resolution microscopy”. In: Inverse Problems 36.1 (2019), p. 014001. doi: 10.1088/1361-6420/ab2a29.
