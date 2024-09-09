---
title: "Radiative-Transfer-based Optical Tomography with Microscope – Modeling and Imaging"
speaker: Yu Zhong
affiliation: Founder & CTO, FINIAC Pte. Ltd., Singapore & Adjunct Associate Professor, Dept. of Physics and Technology, UiT, the Arctic University of Norway, Norway.
date: 2024-09-27 11:00
perso: https://scholar.google.com/citations?user=HklegaMAAAAJ&hl=th
location: new L2S location (IBM building), 3rd floor room
hybrid: https://teams.microsoft.com/l/message/19:178a6f926336444088eb120e42476f36@thread.tacv2/1725911356866?tenantId=61f3e3b8-9b52-433a-a4eb-c67334ce54d5&groupId=10a5c9c7-b271-4ee5-b8eb-3a741d9d89a0&parentMessageId=1725911356866&teamName=S%C2%B3%20Seminar&channelName=General&createdTime=1725911356866
youtube: 
speakerdeck: 
aside: true
---

###### Abstract
The photon transport phenomenon is a dominant physical behavior when light travels through
biological tissues, which can be precisely described by the radiative transfer equation (RTE)
and biological tissues’ optical properties, such as absorption and scattering. RTE has been used
for diffusion optical tomography (DOT) with photons from external light sources and
fluorescence optical tomography (FOT) with internal fluorophores in the tissues emitting
photons. Here we are considering the DOT.
Instead of collecting data on the surface of the tissue as in most DOT, we are working on optical
tomography with data collected by a conventional microscope to find the spatial distribution
of the scattering coefficient of the biological samples. Such work involves two problems: a
forward problem to calculate the measured data with known physical parameters of the sample,
and an inverse problem to retrieve the distribution of the parameter given measured data.
We first present our forward modeling method to simulate the camera image given by a 4f
microscope, by solving RTE within the sample region with the streamline diffusion method
and discrete ordinate method (DOM) first, and then mapping from the radiance on the top
surface of the computational region to the image plane by considering the point spread function
(PSF) of the microscope. We show some simulation results for a simple domain and a synthetic
skin model with layered media and inhomogeneities in different layers observed by a
microscope in the transmission measurement mode. Simulations with different sizes and depths
of the inhomogeneities are proposed, where the PSF effects can be observed.
On the imaging side, we present two methods to achieve inversion of RTE to get the 3D
distribution of the scattering coefficients when the absorption coefficient is neglected, and the
anisotropy factor is assumed to be known. For both methods, notice that the problem is
discretized with the finite volume method (FVM) and DOM.


###### Bio
Dr. Yu Zhong received his Ph.D. in electrical and computer engineering from the
National University of Singapore, Singapore, in 2010. He was a Research Engineer and a
Fellow with the National University of Singapore, from 2009 to 2013, and was involved in a
French-Singaporean MERLION Cooperative Program. From 2014 to 2021, he was a Scientist
at the Institute of High Performance Computing, A*STAR, Singapore. He has been regularly
invited to the Laboratoire des Signaux et Systèmes, Gif-sur-Yvette, France, as an Invited Senior
Scientific Expert, since 2010. He was also a Visiting Professor at the ELEDIA Research Center,
University of Trento, Italy, in 2018. In 2021, he founded his own company FINIAC Pte. Ltd.,
https://finiac.io, focusing on biomedical imaging and sensing with physical wavefields. He is
also an Adjunct Associate Professor at the Department of Physics and Technology, UiT, the
Arctic University of Norway, where his research led in the 3D nanoscopy group
https://www.3dnanoscopy.com/team/ tackles inverse imaging problems under various guises.
He currently serves as Associate Editor of the IEEE Transactions on Geoscience and Remote
Sensing. He has served as a Co-Guest Editor (with Oliver Dorn and Dominique Lesselier) of
the journal Inverse Problems for a special issue “New Trends in Electromagnetic Inverse
Problems” recently completed, 22 papers published in it. Otherwise, he has served as a reviewer
for 20+ top-tier journals in engineering, physics, and applied mathematics. His current research
interests include numerical methods for inverse problems associated with wavefields for
imaging, sensing, and design, electromagnetic and acoustic modeling with complex materials,
and non-destructive testing.
