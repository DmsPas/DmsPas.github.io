---
title: "Improvement of graph partitions using the graph p-laplacian"
collection: talks
type: "Conference talk"
permalink: /talks/pLap_Basel
venue: "Platform for Advanced Scientific Computing (PASC) Conference, Congress Center"
date: 2018-07-03
location: "Basel, Switzerland"
---

[Conference website](https://pasc18.pasc-conference.org/program/index.html)
[Paper link](https://doi.org/10.1145/3218176.3218232)


A continuous formulation of the optimal 2-way graph partitioning based on the p-norm minimization of the graph Laplacian Rayleigh quotient is presented, which provides a sharp approximation to the balanced graph partitioning problem, the optimality of which is known to be NP-hard. The minimization is initialized from a cut provided by a state-of-the-art multilevel recursive bisection algorithm, and then a continuation approach reduces the p-norm from a 2-norm towards a 1-norm, employing for each value of p a feasibility-preserving steepest-descent method that converges on the p-Laplacian eigenvector. A filter favors iterates advancing towards minimum edge-cut and partition load imbalance. The complexity of the suggested approach is linear in graph edges. The simplicity of the steepest-descent algorithm renders the overall approach highly scalable and efficient in parallel distributed architectures. Parallel implementations of recursive bisection on multi-core CPUs and GPUs are presented for large-scale graphs with up to 1.9 billion tetrahedra. The suggested approach exhibits significant improvements over both METIS and KaHIP for graphs originating from various application domains of graph partitioning, ranging from triangular Delaunay meshes to power networks. Particular emphasis is placed on the benefits of applying the p-Laplacian method on graphs emerging from social networks.
