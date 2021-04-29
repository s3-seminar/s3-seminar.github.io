---
title: "Online estimation of elliptical distributions and their mixture: The component-wise information gradient method"
speaker: Jialun Zhou
affiliation: IMS, Groupe Signal Image — CNRS, Université de Bordeaux
date: 2021-05-21 11:00
perso: https://sites.google.com/view/zhoujialun/homepage
online: 
speakerdeck: 
youtube: 
aside: true
---

###### Abstract

Elliptically-Contoured Distributions (ECD) and its Mixture model (MECD) are highly
versatile at modeling general, real-world probability distributions. They have 
therefore played a valuable role in computer vision, image processing, radar signal
processing, and biomedical signal processing. Maximum likelihood estimation (MLE) of 
ECD leads to a system of non-linear equations, most-often addressed using Fixed-Point (FP)
methods. And MECD is usually estimated under Expectation-Maximization (EM) framework
with FP method. Unfortunately, these methods can become impractical, for large-scale 
or high-dimensional datasets (due to lack of time, memory, or computational resources).
To overcome this difficulty, we introduce a Riemannian optimization method, 
the Component-wise Information Gradient. On the one hand, CIG is an online method, so its
recursive nature greatly reduces time and memory consumption. On the other hand, it uses
information geometry to correctly calibrate gradient descent step-sizes, leading to an 
improved rate of convergence. We also mathematically formulate this rate of convergence, 
for two variants of CIG, decreasing or adaptive step-sizes, respectively. It also shows 
that the CIG method compares advantageously to the state-of-the-art, both in computer
experiments, and in practical applications.
