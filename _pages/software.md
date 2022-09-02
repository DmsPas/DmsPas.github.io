---
permalink: /software/
title: "Software"
---

## Sparse QUadratic Inverse Covariance matrix estimation (SQUIC)


<figure><img src="https://drive.google.com/uc?id=14ob4yMPKd6NMcCnxsRT2Otxulpksb0Ay" alt="comp" style="width:100%"><figcaption align = "center"><b>The optimized algorithmic components present in SQUIC.</b></figcaption></figure>

**SQUIC** is an $\ell_1$-regularized maximum likelihood method for performant large-scale sparse precision matrix estimation. The code is packaged as the shared library ``libSQUIC``, intended for Linux and Mac OS. It is written in C++ and is parallelized with OpenMP, with Python and R APIs available.

The shared library can be downloaded and used directly, or compiled from source, from this [link](https://www.gitlab.ci.inf.usi.ch/SQUIC/libSQUIC).



## Spectral clustering for source rocks


<figure><img src="images/map_locations.jpeg" alt="comp" style="width:40%"><figcaption align = "center"><b>Clustering rock extracts from Western Greece’s potential source rocks.</b></figcaption></figure>

Oil-oil and oil-source geochemical correlation is a subject of prime importance to the hydrocarbon exploration community for decades. So far, methods such as k-means, principal component analysis (PCA) and hierarchical clustering (HCA) have been extensively used in chemometrics for such problems. In this work, we present a *direct multiway spectral clustering* approach, which is a *graph based* method that allows the automatic selection of the *optimal number of clusters*.

The MATLAB code can be downloaded and used directly from this [link](https://github.com/DmsPas/Spectral-clustering-of-source-rocks/).

