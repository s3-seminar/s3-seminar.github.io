---
title: "The late-stage training dynamics of (stochastic) subgradient descent on homogeneous neural networks"
speaker: Sholom Schechtman
affiliation: Samovar, Telecom Sud Paris
date: 2024-12-12 14:00
perso: 
location: new L2S location (IBM building), 3rd floor, Salle G. Hopper
hybrid: https://teams.microsoft.com/meet/38868898750167?p=VyI9kngl4zrq6lvHzR
youtube: 
speakerdeck: 
aside: true
---


###### Abstract
We analyze the implicit bias of constant step stochastic subgradient descent (SGD).
We consider the setting of binary classification with homogeneous neural networks -- a large class of deep neural networks with ReLu-type activation functions such as MLPs and CNNs without biases.
Interpreting the dynamics of normalized SGD iterates as an Euler-like discretization of a conservative field flow that is naturally associated to the normalized classification margin,
we show that normalized SGD iterates converge to the set of critical points of the normalized margin at late-stage training
(i.e., assuming that the data is correctly classified with positive normalized margin).
Up to our knowledge, this is the first extension of the analysis of Lyu and Li (2020) on the discrete dynamics of gradient descent to the nonsmooth and stochastic setting.
Our main result applies to binary classification with exponential or logistic losses. We additionally discuss extensions to more general settings. 


