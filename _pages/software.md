---
permalink: /software/
title: "Software"
---

## Sparse QUadratic Inverse Covariance matrix estimation (SQUIC)
<!-- <p align="center">
  <img align="middle" src="[Figures/map_locations.jpeg](http://DmsPas.github.io/images/map_locations.jpeg)" alt="Location of samples" width=":100%"/>
</p> -->

<figure><img align="middle" src="https://drive.google.com/uc?id=14ob4yMPKd6NMcCnxsRT2Otxulpksb0Ay" alt="comp" style="width:100%"><figcaption align = "center"><b>The optimized algorithmic components present in SQUIC.</b></figcaption></figure>

**SQUIC** is an $\ell_1$-regularized maximum likelihood method for performant large-scale sparse precision matrix estimation. The code is packaged as the shared library ``libSQUIC``, intended for Linux and Mac OS. It is written in C++ and is parallelized with OpenMP, with Python and R APIs available.

The shared library can be downloaded and used directly, or compiled from source, from this [link](https://www.gitlab.ci.inf.usi.ch/SQUIC/libSQUIC).



## Spectral clustering for source rocks

<figure><img align="center" src="http://DmsPas.github.io/images/map_locations.jpeg" alt="chrom" style="width:40%"><figcaption align = "center"><b>Potential source rock locations</b></figcaption></figure>
<!-- <p align="center">
  <img align="middle" src="http://DmsPas.github.io/images/Chromatograph.png" alt="Location of samples" width="350"/>
</p> -->

Oil-oil and oil-source geochemical correlation is a subject of prime importance to the hydrocarbon exploration community for decades. We present a direct multiway spectral clustering approach, which is a graph based method that allows the automatic selection of the optimal number of clusters based on the modularity of the resulting partitioning.

The MATLAB code can be downloaded and used directly from this [link](https://github.com/DmsPas/Spectral-clustering-of-source-rocks/).

