---
title: "Large-Scale Optimization for Machine Learning"
speaker: Mher Safaryan
affiliation: Institute of Science and Technology Austria (ISTA)
date: 2025-03-10 15:00
perso: https://avetx.github.io/
location: new L2S location (IBM building), Room Hopper (Third floor)
hybrid: https://teams.microsoft.com/l/meetup-join/19%3a178a6f926336444088eb120e42476f36%40thread.tacv2/1741609746519?context=%7b%22Tid%22%3a%2261f3e3b8-9b52-433a-a4eb-c67334ce54d5%22%2c%22Oid%22%3a%22e0f11e63-ee4e-4782-a35a-1bc88d7e420a%22%7d
aside: true
---


###### Abstract
Mathematical optimization is one of the critical drivers of the success of current machine learning,
where the goal is to minimize the error associated with the machine learning model using a given training
data by optimizing the parameters of that model. In the quest for high-accuracy machine learning models
(such as deep neural networks), both the size of the model and the amount of data necessary to train
the model have hugely increased over time. This has led to massive computational and energy costs for
training and deploying such models.
In this talk, I will present my research on addressing these scaling challenges, which can be categorized
into data scaling and model scaling. For data scaling, efficiently handling large-scale data requires
distributed optimization and federated learning, where training data is spread across multiple machines,
and training is performed in a distributed fashion. However, communication or synchronization between
compute nodes becomes a major bottleneck, limiting scalability. To mitigate this issue, I will discuss
communication-efficient distributed algorithms based on lossy compression, multiple local updates, and
asynchronous communication. For model scaling, I will discuss optimization techniques aimed at reducing
memory consumption throughout the entire training process by compressing optimizer states. Additionally,
I will discuss post-training model compression methods such as distillation, quantization, and pruning,
which improve the efficiency of large-scale model deployment.

