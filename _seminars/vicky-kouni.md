---
title: "The shades of adversarial robustness: from unfolding networks to frame-based attacks"
speaker: Vicky Kouni
affiliation: LAMSADE, Paris Dauphine - PSL
date: 2026-11-13 14:00
perso: https://sites.google.com/view/vasiliki-kouni
location: TBD
hybrid: https://teams.microsoft.com/meet/3394311553605238?p=s72NhSGLIZTcFRFEQe
speakerdeck: 
aside: true
---


###### Abstract
We study adversarial robustness, i.e., resilience of neural networks to
small data/parameter perturbations, in the context of frame theory and
(federated) unfolding. Firstly, we introduce a methodology for creating
structured adversarial data attacks, that highly hurt model robustness.
Our approach hinges upon tools from frame theory – in particular, over-
complete spatial-frequency transforms, which are popular tools for image
processing tasks. By representing the attacks with respect to these transforms, 
we improve their effectiveness, even across unseen, target models. 
We assess the quality of our method on standardized benchmarks,
with results showcasing that our proposed attack outperforms the examined baselines
and exposes vulnerabilities even of defended models, while
highly preserving visual structure. Secondly, we examine unfolding networks: 
state-of-the-art, optimization-inspired solvers for inverse problems,
whose usage can also extend to distributed data via federated learning.
Due to their application in critical domains, unfolding networks necessitate 
robustness guarantees, to ensure reliable (decentralized) recovery in
the presence of adversarial attacks. To that end, we study robust generalization
of a representative class of unfolding networks, under adversarial
data attacks, which jointly occur with parameter corruptions, when the
networks operate in a federated regime. For the latter, we design a jointly
robust federated optimization problem, introducing adversarial federated
unfolding networks. For both centralized and decentralized approaches,
we derive robust generalization guarantees, thus connecting the (joint)
adversarial formulation to performance on unseen data. These guarantees 
provide a principled foundation for devising robust inverse problem
solvers, under a holistic attack framework.
