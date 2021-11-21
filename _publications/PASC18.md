---
title: "Balanced Graph Partition Refinement using the Graph p-Laplacian"
pubtype: "Conference"
collection: publications
permalink: /publication/PASC18
date: 2018-07-02
venue: "PASC' 18: Proceedings of the Platform for Advanced Scientific Computing Conference."
paperurl: 'https://doi.org/10.1145/3218176.3218232'
citation: 'Simpson T, Pasadakis D, Kourounis D, Fujita K, Yamaguchi T, Ichimura T, Schenk O (2018) Balanced graph partition refinement using the graph p-laplacian. In: Proceedings of the Platform for Advanced Scientific Computing Conference, Association for Computing Machinery, New York, NY, USA, PASC ’18'
---

A continuous formulation of the optimal 2-way graph partitioning based on the p-norm minimization of the graph Laplacian Rayleigh quotient is presented, which provides a sharp approximation to the balanced graph partitioning problem, the optimality of which is known to be NP-hard. The minimization is initialized from a cut provided by a state-of-the-art multilevel recursive bisection algorithm, and then a continuation approach reduces the p-norm from a 2-norm towards a 1-norm, employing for each value of p a feasibility-preserving steepest-descent method that converges on the p-Laplacian eigenvector. A filter favors iterates advancing towards minimum edgecut and partition load imbalance. The complexity of the suggested approach is linear in graph edges. The simplicity of the steepest-descent algorithm renders the overall approach highly scalable and efficient in parallel distributed architectures. Parallel implementation of recursive bisection on multi-core CPUs and GPUs are presented for large-scale graphs with up to 1.9 billion tetrahedra. The suggested approach exhibits improvements of up to 52.8% over METIS for graphs originating from triangular Delaunay meshes, 34.7% over METIS and 21.9% over KaHIP for power network graphs, 40.8% over METIS and 20.6% over KaHIP for sparse matrix graphs, and finally 93.2% over METIS for graphs emerging from social networks.




[DOI](https://doi.org/10.1145/3218176.3218232)

