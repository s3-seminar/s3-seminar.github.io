---
title: Divergent-beam backprojection-filtration formula with applications to region-of-interest imaging
speaker: Aymeric Reshef
affiliation: GE Healthcare
date: 2018-05-16 10:30
location: Salle du conseil du L2S
perso: None
speakerdeck: https://speakerdeck.com/s3_seminar/aymeric-reshef
aside: true
---

###### Abstract
Interventional neuroradiology treats vascular pathologies of the brain
through minimally invasive, endovascular procedures. These treatments
are performed under the control of two-dimensional, real-time,
projective X-ray imaging using interventional C-arm systems. Such
systems can perform tomographic acquisitions (which are further used
to reconstruct a three-dimensional image) by rotating the C-arm around
the patient; however, C-arm cone-beam computed tomography (CBCT)
achieves a lower contrast resolution (which is necessary to recover
the clinical information of soft tissues in the brain) than diagnostic
CT, mostly because of dose (thus noise) issues. Interestingly, C-arm
CBCT is often used for region-of-interest (ROI) imaging, again with
limited contrast detection due to truncation artifacts. In this talk,
we revisit the classical direct filtered backprojection (FBP)
reconstruction algorithm and propose a new alternative,
backprojection-filtration (BPF) formula, that is exact in planar
geometries and approximate in the cone-beam geometry. We then apply
this result to the reconstruction of dual-rotation acquisitions,
consisting of a truncated low-noise acquisition with dense angular
sampling, and of additional non-truncated views that are either high-
noise or angularly undersampled. In both cases, the method
successfully improves contrast resolution on digital phantoms and on
real dual-rotation acquisitions of a quality assurance phantom
(Catphan 515).

###### Biography
Aymeric Reshef received his MSc in Mathematics, Vision and Learning
from ENS Cachan in 2014. He joined GE Healthcare (Buc, France) in 2014
for a PhD (CIFRE industrial research agreement) in collaboration with
Télécom ParisTech’s Laboratory for communication and processing of
information (LTCI, Paris, France), supervised by Isabelle Bloch. Since
2018, he is an Image Quality Engineer in the Interventional Guidance
Solutions team at GE Healthcare (Buc, France). His research interests
include image processing, medical physics, tomographic reconstruction
and inverse problems.