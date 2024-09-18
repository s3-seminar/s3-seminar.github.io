---
title: "Convergent plug-and-play methods for image inverse problems."
speaker: Samuel Hurault
affiliation: ENS Paris
date: 2024-10-18 11:00
perso: https://samuelhurault.netlify.app/
location: new L2S location (IBM building), 3rd floor room
hybrid: https://teams.microsoft.com/l/message/19:178a6f926336444088eb120e42476f36@thread.tacv2/1726688296402?tenantId=61f3e3b8-9b52-433a-a4eb-c67334ce54d5&groupId=10a5c9c7-b271-4ee5-b8eb-3a741d9d89a0&parentMessageId=1726688296402&teamName=S%C2%B3%20Seminar&channelName=General&createdTime=1726688296402
youtube: 
speakerdeck: 
aside: true
---

###### Abstract
Plug-and-play methods constitute a class of iterative algorithms for
imaging inverse problems where regularization is performed by an
off-the-shelf Gaussian denoiser. These methods have demonstrated
impressive visual results, particularly when the denoiser is parameterized
by deep neural networks. However, the theoretical convergence of PnP
methods has yet to be fully established. This talk begins with an overview
of the literature on PnP algorithms, followed by the introduction of new
convergence results for these methods when paired with specific denoisers.
Our analysis shows that the resulting PnP algorithms converge to
stationary points of explicit nonconvex functionals. These algorithms are
then applied to various ill-posed inverse problems, including deblurring,
super-resolution, and inpainting. Finally, to address inverse problems
corrupted by Poisson noise, we will introduce a novel Bregman version of
PnP based on the Bregman Proximal Gradient (BPG) optimization algorithm.


###### Bio
I am a postdoctoral researcher at ENS Paris working with with Gabriel Peyré.
I obtained my Ph.D from Université de Bordeaux, co-supervised by Nicolas Papadakis and Arthur Leclaire.
My research interests include image restoration, generative modeling, nonconvex optimization.
The main objective of my PhD was to develop inovative deep denoising priors along with convergent optimization schemes for solving image inverse problems.
I am also one of the main developer of the Python library DeepInv, which provides a unified framework for solving inverse problems using deep neural networks.
