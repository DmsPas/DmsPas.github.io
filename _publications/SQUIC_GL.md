---
title: "Sparse Quadratic Approximation for Graph Learning"
pubtype: "UnderReview"
collection: publications
permalink: /publication/SQUIC_GL
date: 2022-04-26
venue: "TechRxiv"
paperurl: 'https://www.techrxiv.org/articles/preprint/Sparse_Quadratic_Approximation_for_Graph_Learning/19635990'
citation: 'Pasadakis, Dimosthenis; Bollhöfer, Matthias; Schenk, Olaf (2022): Sparse Quadratic Approximation for Graph Learning. TechRxiv. Preprint. https://doi.org/10.36227/techrxiv.19635990.v1'
---

Learning graphs represented by M-matrices via an l1-regularized Gaussian maximum-likelihood method is a popular approach, but also one that poses computational challenges for large scale datasets. Recently proposed methods cast this problem as a constrained optimization variant of precision matrix estimation. In this paper, we build on a state-of-the-art sparse precision matrix estimation method and introduce two algorithms that learn M-matrices, that can be subsequently used for the estimation of graph Laplacian matrices. In the first one, we propose an unconstrained method that follows a post processing approach in order to learn an M-matrix, and in the second one, we implement a constrained approach based on sequential quadratic programming. We also demonstrate the effectiveness, accuracy, and performance of both algorithms. Our numerical examples and comparative results with modern open-source packages reveal that the proposed methods can accelerate the learning of graphs by up to 3 orders of magnitude, while accurately retrieving the latent graphical structure of the data. Furthermore, we conduct large scale case studies for the clustering of COVID-19 daily cases and the classification of image datasets to highlight the applicability in real-world scenarios. 


[DOI](https://doi.org/10.36227/techrxiv.19635990.v1)  



