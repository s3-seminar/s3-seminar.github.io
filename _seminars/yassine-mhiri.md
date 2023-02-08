---
title: A Robust algorithm for radio interferometric imaging
speaker: Yassine Mhiri
affiliation: L2S, SATIE
date: 2023-02-09 10:00
location: Salle du conseil du L2S
hybrid: https://teams.microsoft.com/l/meetup-join/19%3ameeting_M2I4OGY5YjktYzRkNC00OTdkLTlhZDItNzU1ZDhmOWQ3ODMx%40thread.v2/0?context=%7b%22Tid%22%3a%2261f3e3b8-9b52-433a-a4eb-c67334ce54d5%22%2c%22Oid%22%3a%22e7e16d6d-f879-4a2c-9797-8c1ec43541f4%22%7d
perso: y-mhiri.github.io
feature_image: "yassine-mhiri.png"
image: "seminars/yassine-mhiri/yassine-mhiri.png"
aside: true
---

###### Abstract

Radio interferometers produce images of the sky in the radio domain bringing new insights into various scientific domains such as solar monitoring, planetology, and astrophysics. A new generation of large-scale radio interferometers are designed with the promise to improve further the resolution and sensitivity of radio astronomical images. Nevertheless, these technological advances bring several signal processing challenges to exploit the scientific potential of such instruments fully.

Amongst them image synthesis can be expressed as a signal reconstruction problem from incomplete Fourier measurements and leads to an ill-posed inverse problem. The particularity of radio interferometric data lie in the coverage of the Fourier space (UV-coverage) that depends on the sensors coordinates as well as the observation time. In particular, large-scale radio interferometers will improve the UV coverage, increasing the amount of data to process. Most imaging algorithm can often be expressed as a regularized convex optimization algorithm that considers an L2 norm as fitting term, implicitely assuming a Gaussian noise on the measurements. However, additive perturbations of radio-interferometric data cannot be effectively modeled by a Gaussian noise.

In this talk, we'll explore the basics of radio interferometric imaging and present a robust imaging algorithm. We will consider compound Gaussians to model the presence of outliers in the data, and derive an expectation-maximization algorithm to compute image estimates from the measured visibilities. Finally, numerical results on realistic data that illustrate the performance of the proposed algorithm will be shown.


###### References

A Robust EM Algorithm for Radio Interferometric Imaging in The Presence of Outliers. Yassine Mhiri, Pascal Larzabal, Mohammed-Nabil El Korso, Arnaud Breloy SiPS22, Nov 2022, Rennes, France.


###### Biography

I am a Phd Student in statistical signal processing applied to radioastronomy, supervised by Pascal Larzabal, Mohammed Nabil EL Korso and Arnaud Breloy within the signal processing group (MOSS) of the SATIE laboratory at Paris-Saclay University. Before that, I was a research engineer at Phasics where i helped conceive and develop algorithmic solutions for wavefront sensor analysis.

My current research interests lie in robust signal processing, statistical learning, structured covariance matrix estimation, interferometry and sensor array processing.
