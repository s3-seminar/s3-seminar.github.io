---
title: "Contrastive Learning in Medical Imaging - A metric learning approach"
speaker: Pietro Gori
affiliation: Téléom Paris, France
date: 2023-06-30 11:00
perso: https://perso.telecom-paristech.fr/pgori/
location: "Salle des séminaires du L2S"
hybrid: https://teams.microsoft.com/l/meetup-join/19%3a178a6f926336444088eb120e42476f36%40thread.tacv2/1681737246400?context=%7b%22Tid%22%3a%2261f3e3b8-9b52-433a-a4eb-c67334ce54d5%22%2c%22Oid%22%3a%224d6c63a8-7eae-4099-804e-68bcb968bec0%22%7d
youtube: 
speakerdeck: https://speakerdeck.com/s3_seminar/pietro-gori
aside: true
---

<div style="text-align:center">
<script async class="speakerdeck-embed" data-id="0cf2383c24bd4278aa0b7808bd5162aa" data-ratio="1.33333333333333" src="//speakerdeck.com/assets/embed.js"></script></div>


###### Abstract

Contrastive Learning (CL) is a paradigm designed for self-supervised representation learning which has been applied to unsupervised,
weakly supervised and supervised problems.
The objective in CL is to estimate a parametric mapping function that maps positive samples (semantically similar) close together
in the representation space and negative samples (semantically dissimilar) far away from each other.
In general, positive samples can be defined in different ways depending on the problem:
transformations (i.e., augmentations) of the same image (unsupervised setting), samples belonging to the same class (supervised)
or with similar image attributes (weakly-supervised). The definition of negative samples varies accordingly.

In this talk, we will show how a metric learning approach for CL allows us to:
1- better formalize recent contrastive losses, such as InfoNCE and SupCon,
2- derive new losses for unsupervised, supervised, and weakly supervised problems, both classification and regression,
and 3- propose new regularization terms for debiasing.

Furthermore, leveraging the proposed metric learning approach and kernel theory, we will describe a novel loss, called decoupled uniformity,
that allows the integration of prior knowledge, given either by generative models or weak attributes,
and removes the positive-negative coupling problem, as in the InfoNCE loss.
 
We validate the usefulness of the proposed losses on standard vision datasets and medical imaging data.


###### References
C. A. Barbano, B. Dufumier, E. Tartaglione, M. Grangetto, P. Gori
Unbiased Supervised Contrastive Learning
ICLR, 2023 
 
C. A. Barbano, B. Dufumier, E. Duchesnay, M. Grangetto, P. Gori
Contrastive learning for regression in multi-site brain age prediction
IEEE ISBI, 2023 
 
E. Sarfati, A. Bône, M.-M. Rohé, P. Gori, I. Bloch
Learning to diagnose cirrhosis from radiological and histological labels with joint self and weakly-supervised pretraining strategies
IEEE ISBI, 2023 
 
C. Ruppli, P. Gori, R. Ardon, I. Bloch
Optimizing transformations for contrastive learning in a differentiable framework
MILLanD workshop (MICCAI), 2022 
 
B. Dufumier, P. Gori, J. Victor, A. Grigis, E. Duchesnay
Conditional Alignment and Uniformity for Contrastive Learning with Continuous Proxy Labels
MedNeurIPS, 2021
 
B. Dufumier, P. Gori, J. Victor, A. Grigis, E. Duchesnay
Contrastive Learning with Continuous Proxy Meta-Data for 3D MRI Classification
MICCAI, 2021


###### Biography

Pietro Gori is Maître de Conférences in Artificial Intelligence and Medical Imaging at Télécom Paris (IPParis) in the IMAGES group.
He did his academic training with Inria at the ARAMIS Lab in Paris and then at Neurospin (CEA).
Previous to that, he obtained a MSc in Mathematical Modelling and Computation from the DTU in Copenhagen
and a MSc in Biomedical Engineering from the University of Padova. He participated to the development of the open source software suite deformetrica
for statistical shape analysis and of the software platform Clinica for clinical neuroimaging studies.
His research interests lie primarily in the fields of machine learning, AI, representation learning, medical imaging and computational anatomy.
He has 45 publications in international peer-reviewed journals or conferences and had/has the pleasure to work with 10 Master students,
14 PhD students and 2 post-docs.
