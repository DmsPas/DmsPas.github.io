---
permalink: /software/
title: ""
---

## NPR for local graph partitioning

<p align="center">
  <img src="http://DmsPas.github.io/images/Gauss8_nodes.png"  alt="Initial data" width="302"/>
  <img src="http://DmsPas.github.io/images/Gauss_Clusters_re.png" alt="p Clusters" width="350"/>
</p>
<center>
We developed a new method for local graph partitioning based on a nonlinear generalisation of the PageRank problem involving the Moore-Penrose inverse of the incidence matrix. The Levenberg-Marquardt method is used with a full rank Jacobian variant to obtain a numerical solution to the generalised problem. Sets of vertices are formed according to the ranking supplied by the solution, and a conductance criterion decides upon the set that best represents the local cluster around a starting vertex.
</center>

The MATLAB code and the input graphs are available [here](https://github.com/DmsPas/Nonlinear_modified_PageRank).


## Sparse QUadratic Inverse Covariance matrix estimation (SQUIC)

<p align="center">
  <img align="middle" src="http://DmsPas.github.io/images/SQUIC_components.png" alt="Algo comp" width="650"/>
</p>

**SQUIC** is an $\ell_1$-regularized maximum likelihood method for performant large-scale sparse precision matrix estimation. The code is packaged as the shared library ``libSQUIC``, intended for Linux and Mac OS. It is written in C++ and is parallelized with OpenMP, with Python and R APIs available.

The shared library can be downloaded and used directly, or compiled from source, from this [link](https://www.gitlab.ci.inf.usi.ch/SQUIC).



## Spectral clustering for source rocks

<p align="center">
  <img align="middle" src="http://DmsPas.github.io/images/map_locations.jpeg" alt="Location of samples" width="250"/>
</p>

Oil-oil and oil-source geochemical correlation is a subject of prime importance to the hydrocarbon exploration community for decades. We present a direct multiway spectral clustering approach, which is a graph based method that allows the automatic selection of the optimal number of clusters based on the modularity of the resulting partitioning.

The MATLAB code can be downloaded and used directly from this [link](https://github.com/DmsPas/Spectral-clustering-of-source-rocks/).


## Multiway p-spectral graph cuts on Grassmann manifolds

<p align="center">
  <img src="http://DmsPas.github.io/images/Figure_Worms_Initial_img.jpg"  alt="Initial data" width="350"/>
  <img src="http://DmsPas.github.io/images/Figure_Worms_Clusters_img.jpg" alt="p Clusters" width="350"/>
</p>

In this work, we developed a new method for multiway p-spectral clustering that leverages recent advancements in Riemannian optimization. This was achieved by reformulating the problem of obtaining multiple eigenvectors of the graph p-Laplacian as an unconstrained minimization problem on a Grassmann manifold.

The MATLAB code with mex executables can be downloaded and used directly from this [link](https://github.com/DmsPas/Multiway-p-spectral-clustering).