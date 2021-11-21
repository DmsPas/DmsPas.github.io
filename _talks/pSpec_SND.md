---
title: "Multiway p-spectral graph cuts  on Grassmann Manifolds"
collection: talks
type: "Conference talk"
permalink: /talks/pSpec_SND
venue: "Swiss Numerics Day (SND), EPFL"
date: 2021-09-13
location: "Lausanne, Switzerland"
---

[Event website](https://snd2021.epfl.ch/program.html)
[Slides](http://DmsPas.github.io/files/SIAM_LA21.pdf)

The representantion of data in the form of graphs [1] and their separation into groups is a ubiquitous task in every scientific domain that deals with interact- ing or interconnected data. Spectral clustering and its nonlinear reformulations have gained a lot of attention due to their increased numerical benefits and solid mathematical background. In this talk we present a direct multiway spectral clustering algorithm in the p-norm, for p ∈ (1,2]. The problem of comput- ing multiple eigenvectors of the graph p-Laplacian, a nonlinear generalization of the standard graph Laplacian, is recasted as an unconstrained minimization problem on a Grassmann manifold and solved with a state-of-the-art library for Riemannian optimization. The value of p is reduced in a pseudocontinuous manner, promoting sparser solution vectors that correspond to optimal graph cuts as p approaches one. Monitoring the monotonic decrease of the balanced graph cuts guarantees that we obtain the best available solution from the p-levels considered. We demonstrate the effectiveness and accuracy of our algorithm in various synthetic test-cases. Our numerical examples and comparative results with eigenvector-based clustering methods indicate that the proposed method obtains high quality clusters both in terms of balanced graph cut metrics and in terms of the accuracy of the labelling assignment. Furthermore, we will demon- strate studies for the classification of facial images and handwritten characters to showcase the applicability in real-world datasets.


