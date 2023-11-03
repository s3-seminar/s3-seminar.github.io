---
title: "Riemannian geometry for statistical estimation and learning: applications to remote sensing and M/EEG data analysis"
speaker: Antoine Collas
affiliation: MIND team, Inria Saclay
date: 2023-11-24 11:00
perso: https://www.antoinecollas.fr/
location: new L2S location (IBM building), room to be announced
hybrid: https://teams.microsoft.com/l/meetup-join/19%3a178a6f926336444088eb120e42476f36%40thread.tacv2/1699051172476?context=%7b%22Tid%22%3a%2261f3e3b8-9b52-433a-a4eb-c67334ce54d5%22%2c%22Oid%22%3a%224d6c63a8-7eae-4099-804e-68bcb968bec0%22%7d
youtube: 
speakerdeck: 
aside: true
---

###### Abstract


Covariance matrices have emerged as a robust and versatile tool for the statistical analysis of multivariate data, particularly in the domains of M/EEG data analysis.
These matrices, being positive definite, can be viewed as points residing on a Riemannian manifold, opening up a new avenue for understanding and harnessing their properties.

In this talk, we begin by introducing a machine learning pipeline, encompassing clustering, classification, and regression, all within the framework of Riemannian geometry.
Indeed, we explore several innovative extensions of this pipeline.
Firstly, we introduce new divergence measures, based on geodesic triangles between pairs of location-covariance matrices [1].
Additionally, we present a novel, robust estimator for jointly estimating location and covariance matrices [2], which promises to improve robustness to outliers.
We also discuss the classification of descriptors following this model.
Furthermore, our discussion will conduct us into domain adaptation techniques specifically tailored for regression tasks [3],
shedding light on how Riemannian geometry can be applied to adapt to different data domains.

To demonstrate the effectiveness of these methods, we apply them to recent datasets from the fields of remote sensing and M/EEG data analysis, showcasing their real-world utility and versatility.

In the conclusion, we discuss open-source ecosystem surrounding Riemannian geometry for the statistical analysis of multivariate data with Geomstats, Pymanopt and pyCovariance.

###### References

[1] A. Collas, F. Bouchard, G. Ginolhac, A. Breloy, C. Ren, and J.-P. Ovarlez, On the use of geodesic triangles between gaussian distributions for classification problems, in ICASSP, Singapore, 2022.

[2] A. Collas, A. Breloy, C. Ren, G. Ginolhac, and J.-P. Ovarlez, Riemannian optimization for non-centered mixture of scaled Gaussian distributions, IEEE Transactions on Signal Processing, 2023.

[3] A. Mellot, A. Collas, P. L. Rodrigues, D. Engemann, and A. Gramfort, Harmonizing and aligning M/EEG datasets with covariance-based techniques to enhance predictive regression modeling, Submitted to Imaging Neuroscience MIT Press, 2023.
