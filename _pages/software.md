---
permalink: /software/
title: "Software"
---

## Sparse QUadratic Inverse Covariance matrix estimation (SQUIC)

<p align="center">
  <img align="middle" src="http://DmsPas.github.io/images/SQUIC_components.png" alt="Algo comp" width="550"/>
</p>
<center>
<!--  -->
</center>

<!-- <figure><img align="middle" src="https://drive.google.com/uc?id=14ob4yMPKd6NMcCnxsRT2Otxulpksb0Ay" alt="comp" style="width:100%"><figcaption align = "center"><b>The optimized algorithmic components present in SQUIC.</b></figcaption></figure> -->

**SQUIC** is an $\ell_1$-regularized maximum likelihood method for performant large-scale sparse precision matrix estimation. The code is packaged as the shared library ``libSQUIC``, intended for Linux and Mac OS. It is written in C++ and is parallelized with OpenMP, with Python and R APIs available.

The shared library can be downloaded and used directly, or compiled from source, from this [link](https://www.gitlab.ci.inf.usi.ch/SQUIC/libSQUIC).



## Spectral clustering for source rocks

<p align="center">
  <img align="middle" src="http://DmsPas.github.io/images/map_locations.jpeg" alt="Location of samples" width="250"/>
</p>
<center>
<!--  -->
</center>

<!-- <figure><img align="center" src="http://DmsPas.github.io/images/map_locations.jpeg" alt="chrom" style="width:40%"><figcaption align = "center"><b>Potential source rock locations</b></figcaption></figure> -->


Oil-oil and oil-source geochemical correlation is a subject of prime importance to the hydrocarbon exploration community for decades. We present a direct multiway spectral clustering approach, which is a graph based method that allows the automatic selection of the optimal number of clusters based on the modularity of the resulting partitioning.

The MATLAB code can be downloaded and used directly from this [link](https://github.com/DmsPas/Spectral-clustering-of-source-rocks/).


## Multiway p-spectral graph cuts on Grassmann manifolds

<p align="center">
  <img src="http://DmsPas.github.io/images/Figure_Worms_Initial_img.jpg"  alt="Initial data" width="350"/>
  <img src="http://DmsPas.github.io/images/Figure_Worms_Clusters_img.jpg" alt="p Clusters" width="350"/>
</p>
<center>
<!--  -->
</center>

In this work, we developed a new method for multiway p-spectral clustering that leverages recent advancements in Riemannian optimization. This was achieved by reformulating the problem of obtaining multiple eigenvectors of the graph p-Laplacian as an unconstrained minimization problem on a Grassmann manifold.

The MATLAB code with mex executables can be downloaded and used directly from this [link](https://github.com/DmsPas/Multiway-p-spectral-clustering).

