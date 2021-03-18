---
title: "Speeding up of kernel-based learning for high-order tensor"
speaker: "Ouafae Karmouda"
affiliation: "SIGMA team at CRIStAL laboratory, Lille"
date: 2021-03-12 11:00
online: https://teams.microsoft.com/l/meetup-join/19%3a178a6f926336444088eb120e42476f36%40thread.tacv2/1614181583266?context=%7b%22Tid%22%3a%2261f3e3b8-9b52-433a-a4eb-c67334ce54d5%22%2c%22Oid%22%3a%22f214f106-92ec-433a-b9a8-20a164143534%22%7d
perso: 
feature_image: "ouafae-karmouda.jpg"
image: "seminars/ouafae-karmouda/ouafae-karmouda.jpg"
aside: true
youtube: https://www.youtube.com/watch?v=XXWSmTa9BhY
speakerdeck: https://speakerdeck.com/s3_seminar/ouafae-karmouda
---

<div style="text-align:center">
<script async class="speakerdeck-embed" data-id="80fa4123463941eb8484dccad765fb7f" data-ratio="1.33333333333333" src="//speakerdeck.com/assets/embed.js"></script>
</div>

###### Abstract

Supervised learning is a major task to classify datasets. In our context, we are interested into classification from high-order tensors datasets. The “curse of dimensionality” states that the complexities in terms of storage and computation grow exponentially with the order. As a consequence, the method from the state-of-art based on the Higher-Order SVD (HOSVD) works well but suffers from severe limitation in terms of complexities. In this work, we propose a fast Grassmannian kernel-based method for high-order tensor learning based on the equivalence between the Tucker and the tensor-train decompositions. Our solution is linked to the tensor network, where the aim is to break the initial high-order tensor into a collection of low-order tensors (at most 3-order). We show on several real datasets that the proposed method reaches a similar accuracy classification rate as the Grassmannian kernel-based method based on the HOSVD but for a much lower complexity.

###### References

Ouafae Karmouda, Jérémie Boulanger, Remy Boyer. Speeding up of kernel-based learning for high-order tensors. 2021 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), Jun 2021, Toronto (virtual), Canada.
Available: https://hal.univ-lille.fr/hal-03126008.

###### Biography

Ouafae Karmouda receives a Master’s degree in Applied Mathematics from the Faculty of Science and Technologies of Fes, Morocco, in 2018. She receives a Master's degree in Data Science from the Aix-Marseille University in 2019. Currently, she is a second year PhD student under the supervision of Rémy Boyer and Jérémie Boulanger in SIGMA team at CRIStAL laboratory, Lille. Her research interests focus on developping/improving Maching learning Algorithms for multidimensional data (tensors). She is particulary interested in kernel methods and Deep Learning techniques for high dimensional data. The challenge when dealing with tensors lies in the « curse of dimensionality ». In other words, the computational complexity grows exponentially with the order of tensors. To mitigate this issue, she is interested in Tensor network models and particularly the Tensor Train decomposition.
