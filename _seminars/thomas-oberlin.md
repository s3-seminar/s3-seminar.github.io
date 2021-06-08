---
title: "Regularization via deep generative models: an analysis point of view"
speaker: Thomas Oberlin
affiliation: ISAE-SUPAERO, ANITI, IRIT
date: 2021-06-25 11:00
image: "seminars/thomas-oberlin/thomas-oberlin.jpg"
feature_image: "thomas-oberlin.jpg"
perso: https://personnel.isae-supaero.fr/thomas-oberlin/
online: 
aside: true
---

###### Abstract

In this talk, we present a new way of regularizing an inverse problem in imaging
(e.g., deblurring or inpainting) by means of a deep generative neural network.
Compared to end-to-end models, such approaches seem particularly interesting
since the same network can be used for many different problems and experimental
conditions, as soon as the generative model is suited to the data. Previous
works proposed to use a synthesis framework, where the estimation is performed
on the latent vector, the solution being obtained afterwards via the decoder.
Instead, we propose an analysis formulation where we directly optimize the image
itself and penalize the latent vector. We illustrate the interest of such a
formulation by running experiments of inpainting, deblurring and
super-resolution. In many cases our technique achieves a clear improvement of
the performance and seems to be more robust, in particular with respect to
initialization.

###### References

Oberlin, T., & Verm, M. (2021). Regularization via deep generative models: an
analysis point of view. To appear in ICIP 2021, https://arxiv.org/abs/2101.08661

###### Biography

Thomas Oberlin holds a Ph.D. in applied mathematics from the University of
Grenoble. In 2014, he was a postdoctoral fellow in signal processing and
medical imaging at Inria Rennes, before joining as an Assistant Professor INP
Toulouse - ENSEEIHT and the IRIT Laboratory, at Université de Toulouse. Since
2019, he is an Assistant/Associate Professor of Image Processing and Machine
Learning at ISAE-SUPAERO and member of IA institute ANITI. His research
interests include hyperspectral/spectral imaging, latent factor models,
data-driven regularization of inverse problems, and time-frequency
representations.
