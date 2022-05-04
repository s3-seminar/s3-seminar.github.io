---
title: "Probabilistic PCA for heterogeneous-quality data"
speaker: David Hong
affiliation: Department of Statistics and Data Science, University of Pennsylvania, Philadelphia, PA, US
date: 2022-05-12 15:00
perso: https://dahong.gitlab.io
online: https://teams.microsoft.com/l/meetup-join/19%3a178a6f926336444088eb120e42476f36%40thread.tacv2/1651683980053?context=%7b%22Tid%22%3a%2261f3e3b8-9b52-433a-a4eb-c67334ce54d5%22%2c%22Oid%22%3a%224d6c63a8-7eae-4099-804e-68bcb968bec0%22%7d
youtube: 
speakerdeck: 
aside: true
---

###### Abstract

Principal component analysis (PCA) is a workhorse method for identifying low-dimensional (i.e., low-rank) structure in noisy data
and is ubiquitous in signal processing. However, it estimates the underlying low-rank structure sub-optimally when the samples 
have heterogeneous quality, as is common in modern applications. 
PCA treats all samples uniformly so its performance degrades when the noise is heteroscedastic across samples, 
as occurs, e.g., when data come from different sources that are of different quality. 
This talk presents a new probabilistic PCA variant that estimates and accounts for this heterogeneity by incorporating it in the statistical model. 
Unlike the usual (homoscedastic) setting, it seems that the resulting nonconvex optimization problem is not solved by the singular value decomposition. 
We develop a heteroscedastic probabilistic PCA technique (HePPCAT) that uses efficient alternating maximization 
to jointly estimate both the underlying low-rank structure and the unknown noise variances. 
Efficiently updating the noise variance estimates presents an interesting challenge; 
we develop several methods and carefully study their trade-offs through numerical experiments. 
Finally, we illustrate how accounting for heteroscedasticity enables HePPCAT to substantially outperform (homoscedastic) PCA approaches.


###### References

HePPCAT: Probabilistic PCA for Data with Heteroscedastic Noise.
David Hong, Kyle Gilman, Laura Balzano, Jeffrey A. Fessler.
IEEE Transactions on Signal Processing, 2021. https://doi.org/10.1109/TSP.2021.3104979


###### Biography

David Hong completed his B.S. in ECE and mathematics at Duke University under the Benjamin N. Duke full scholarship. 
He completed his Ph.D. in EECS at the University of Michigan under the NSF Graduate Research Fellowship. 
He is now an NSF Mathematical Sciences Postdoctoral Fellow in the Department of Statistics and Data Science at the University of Pennsylvania.
His broad interests lie in the foundations of data science and include low-rank matrix and tensor methods for high-dimensional and heterogeneous data.

