---
title: "Modeling the City: Generative AI for Multivariate Traffic Scenario Generation"
speaker: Michele Carbonera
affiliation: University of Milano-Bicocca
date: 2024-12-05 11:00
perso: 
location: new L2S location (IBM building), 3rd floor, Salle G. Hopper
hybrid: https://teams.microsoft.com/meet/3722450464943?p=l5WfJe8jtmrf7RDSUa
youtube: 
speakerdeck: 
aside: true
---


###### Abstract
Urban transportation systems are becoming increasingly complex, driven by rapid urbanization, multimodal mobility demands, and dynamic traffic patterns.
In this evolving context, the ability to simulate diverse and realistic traffic conditions is essential for evaluating adaptive strategies,
optimizing infrastructures, and supporting resilient decision making processes under uncertainty.
A key element in this process is scenario generation, understood as the creation of synthetic data instances that closely resemble empirical observations while
preserving their essential statistical properties.
In our setting, this involves modeling a multivariate random variable defined over a spatial domain,
where each component represents the speed observed on a specific road segment.
The goal is to generate coherent instances that maintain both the marginal distributions of individual road segments and the spatial dependencies embedded in
real-world traffic data.

In the literature, traditional statistical approaches, such as Gaussian copulas, have been widely adopted to approximate the multivariate distributions [1].
However, these methods involve prior assumptions and fixed parametric forms, and their computational cost increases significantly with problem size.
Consequently, they struggle to scale effectively in large urban traffic networks, where data dimensionality is high and spatial dependencies are complex.

To overcome these limitations, we investigate a range of deep generative architectures grounded in the Variational Autoencoder (VAE) framework [5].
Our methodology builds on three core components.
First, we enhance the training process by incorporating distribution-sensitive terms into the loss function,
aiming to improve the statistical alignment between generated and empirical scenarios.
Second, we explicitly encode the topological structure of the road network using graph-based architectures (e.g., Graph Convolutional Networks),
which are particularly effective in capturing local dependencies and spatially structured patterns [4].
Third, we introduce attention mechanisms (e.g., Transformers) that operate either on top of or independently from the graph structure,
enabling the modeling of non-local interactions and long-range dependencies that are often critical in complex urban traffic systems.

Evaluating the quality of generated data in high-dimensional settings presents a non-trivial challenge.
To address this, we adopt a multi-perspective evaluation strategy that integrates both quantitative and qualitative criteria to
assess the coherence, diversity, and realism of the generated scenarios.
Experiments are conducted on real-world datasets, including widely used public benchmarks (PEMS-BAY and METR-LA [3])
and large-scale urban traffic dataset (Chengdu [2]).
These datasets span across diverse spatial configurations and traffic regimes, enabling a thorough assessment of model behavior across
varying levels of complexity and highlighting its scalability in realistic operational contexts.

Empirical results show that hybrid VAE architectures, particularly those augmented with attention mechanism,
more effectively reproduce the multivariate characteristics of observed traffic data, while offering improved scalability and
faster sample generation compared to classical copula-based approaches.
Overall, the proposed generative VAE models offer a scalable and effective framework for realistic scenario generation in high-dimensional contexts,
as in the case of urban road traffic networks examined in this study.

###### References
[1] Jacob Feldman and Daniel R. Kowal. Nonparametric copula models for multivariate, mixed, and missing data. Journal of Machine Learning Research, 25:1–50, 2024.

[2] Cong Guo, Bo Yang, Shuguang Wang, Qingquan Li, and Jie Cao. Urban link travel speed dataset from a megacity road network. Scientific Data, 6(1):262, 2019.

[3] H. He and X. Jiang. California traffic network datasets: Metr-la, pems-bay, pems04 and pems08 for traffic speed and flow analysis. IEEE DataPort, 2025.

[4] C. Jia, F. Jiang, Z. Chen, R. Wang, and Y. Xiao. A dynamic traffic flow prediction method based on spatio-temporal graph transformer. Applied Intelligence, 55:1048, 2025.

[5] Diederik P. Kingma and Max Welling. Auto-encoding variational bayes. arXiv preprint arXiv:1312.6114, 2013.
