---
title: "Robust low-rank covariance matrix estimation with missing values and application to classification problems"
speaker: Alexandre Hippert-Ferrer
affiliation: L2S, CentraleSupelec, Université Paris Saclay
date: 2021-09-24 11:00
perso: https://ahippert.github.io/
online: https://teams.microsoft.com/l/meetup-join/19%3a178a6f926336444088eb120e42476f36%40thread.tacv2/1631110344129?context=%7b%22Tid%22%3a%2261f3e3b8-9b52-433a-a4eb-c67334ce54d5%22%2c%22Oid%22%3a%224d6c63a8-7eae-4099-804e-68bcb968bec0%22%7d
speakerdeck: 
aside: true
---


###### Abstract

Missing values are inherent to real-world data sets. Statistical learning problems often require the estimation of parameters as the mean or the covariance matrix (CM).
If the data is incomplete, new estimation methodologies need to be designed depending on the data distribution and the missingness pattern (i.e. the pattern describing which values are missing with respect to the observed data).
This talk considers robust CM estimation when the data is incomplete.
In this perspective, classical statistical estimation methodologies are usually built upon the Gaussian assumption, whereas existing robust estimation ones assume unstructured signal models.
The former can be inaccurate in real-world data sets in which heterogeneity causes heavy-tail distributions, while the latter does not profit from the usual low-rank structure of the signal.
Taking advantage of both worlds, a CM estimation procedure is designed on a robust (compound Gaussian) low-rank model by leveraging the observed-data likelihood function within an expectation-maximization (EM) algorithm.
After a validation on simulated data sets with various missingness patterns, the interest the proposed procedure is shown for CM-based classification and clustering problems with incomplete data.
Investigated examples generally show higher classification accuracies with a classifier based on robust estimation compared to the one based on Gaussian assumption and the one based on imputed data.


