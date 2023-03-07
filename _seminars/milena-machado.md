---
title: Time series, principal component analysis and logistic regression: An application to the association between annoyance and air pollution
speaker: Milena Machado
affiliation: Federal Institute of Science and Technology
date: 2023-03-16 10:00
location: Salle des séminaires du L2S
hybrid: https://teams.microsoft.com/l/meetup-join/19%3ameeting_YWM4ZjU0ODEtOTkzOC00ZTNlLWE1YzgtNTllOGUyNDk4NGFh%40thread.v2/0?context=%7b%22Tid%22%3a%2261f3e3b8-9b52-433a-a4eb-c67334ce54d5%22%2c%22Oid%22%3a%22e7e16d6d-f879-4a2c-9797-8c1ec43541f4%22%7d
perso: https://lattes.cnpq.br/7056788837736672
feature_image: "yassine-mhiri.png"
image: "seminars/milena-machado/milena-machado.png"
aside: true
---

###### Abstract

Several studies applied regression models to quantify the relationship between annoyance from environmental stressors and measured levels of these stressors, such as odors (Blanes-Vidal, 2015), noise (Klaeboe et al., 2000), vibration (Klaeboe et al., 2003) and various air pollutants (Rotko et al. 2002; Llop et al., 2008; Amundsen et al., 2008; Nikolopoulou et al., 2011; Machado et al. 2018). Most of these authors have used linear and logistic regression techniques to establish a relationship between annoyance and concentration levels of air pollutants, considering only one pollutant in the model as a single covariate. In this talk, we will consider multiple pollutants covariates. These covariates are generally physically and statistically correlated, implying multicollinearity and, therefore, inflation of the variance of the estimators and spurious results.

The objective of this work is to propose a combination of a time series model (VAR-1), principal components analysis (PCA), and binary logistic regression to estimate the annoyance caused by particulate matter using more than one pollutant (PM10, TSP, and PS) in the same model. As Zamprogno (2020) pointed out, the PCA technique requires variables not correlated in time, i. e., serially independent. In practice, air pollutant concentrations can hardly be assumed uncorrelated or stationary.

This work uses a time series model to transform the original air pollutants data in time uncorrelated data (white noise) before applying the PCA technique. By the filtering analysis (VAR (1)) and PCA technique, it is possible to obtain components (linear combination of air pollutants) that are uncorrelated in time and between them. Then, applying multiple logistic regression allows us to calculate the relative risk (RR) of annoyance for each pollutant involved in the model. The relative risk estimates confirm that, in general, an increase in air pollutant concentrations significantly contributes to increasing the probability of being annoyed.

These results provide evidence of a significant correlation between perceived annoyance and groups of particulate matter. This study offers scientific arguments for policymakers to force some industries to reduce the emission of pollutants that generate nuisance and health risks.

###### Reference

Zamprogno, B., Reisen, V. A., Bondon, P., Aranda Cotta, H. H., & Reis Jr, N. C. (2020). Principal component analysis with autocorrelated data. Journal of Statistical Computation and Simulation, 90(12), 2117-2135.

###### Biography

I am Associate Professor at the Federal Institute of Science and Technology of ES – IFES. I am collaborator researcher at NQUALIAR (Group for Air Quality Studies) and collaborator researcher at NUMES (Stochastics Modeling Study Group). At the moment, I am a visiting researcher at the L2S supervised by prof. Pascal Bondon I have been studying/working and interested in: multivariate statistical techniques, such as Times Series Analysis, Principal Component Analysis, Multiple Correspondence Analysis, Logistic Regression Models, and others. The main areas of applications are Environmental Engineering (Air quality area), health science (Epidemiological area), with a special interest in problems of atmospheric pollution.
