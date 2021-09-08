---
title: "Robust low-rank covariance matrix estimation with missing values and application to classification problems"
speaker: Alexandre Hippert-Ferrer
affiliation: L2S, CentraleSupelec, Université Paris Saclay
date: 2021-09-24 11:00
image: 
feature_image: 
perso: https://ahippert.github.io/
online: https://teams.microsoft.com/l/meetup-join/19%3a178a6f926336444088eb120e42476f36%40thread.tacv2/1623242140099?context=%7b%22Tid%22%3a%2261f3e3b8-9b52-433a-a4eb-c67334ce54d5%22%2c%22Oid%22%3a%22e7e16d6d-f879-4a2c-9797-8c1ec43541f4%22%7d
youtube: 
speakerdeck: 
aside: true
---

<div style="text-align:center">
<script async class="speakerdeck-embed" data-id="a4fac20caf2c4377912e7f48d296168b" data-ratio="1.33333333333333" src="//speakerdeck.com/assets/embed.js"></script>
</div>

###### Abstract

Missing values are inherent to real-world data sets. Statistical learning problems often require the estimation of parameters as the mean or the covariance matrix (CM).
If the data is incomplete, new estimation methodologies need to be designed depending on the data distribution and the missingness pattern (i.e. the pattern describing which values are missing with respect to the observed data).
This talk considers robust CM estimation when the data is incomplete.
In this perspective, classical statistical estimation methodologies are usually built upon the Gaussian assumption, whereas existing robust estimation ones assume unstructured signal models.
The former can be inaccurate in real-world data sets in which heterogeneity causes heavy-tail distributions, while the latter does not profit from the usual low-rank structure of the signal.
Taking advantage of both worlds, a CM estimation procedure is designed on a robust (compound Gaussian) low-rank model by leveraging the observed-data likelihood function within an expectation-maximization (EM) algorithm.
After a validation on simulated data sets with various missingness patterns, the interest the proposed procedure is shown for CM-based classification and clustering problems with incomplete data.
Investigated examples generally show higher classification accuracies with a classifier based on robust estimation compared to the one based on Gaussian assumption and the one based on imputed data.


