---
title: "Archive-based Swarms"
date: 2020-07-12T13:30:34+05:30
tags: [artificial neural networks, fitness-distance ratio, archive, swarm intelligence, evolutionary machine learning, particle swarm optimization, premature convergence]
---
The Particle Swarm Optimization (PSO) algorithm updates each individual's velocity and position using its own prior best position and the best position found so far by any particle. Effective search for global optima can benefit if each particle may utilize additional historical information regarding the quality of previously visited positions in its proximity. We present an approach for doing so, using an archive containing some prior particle positions, analogous to the archive used in some multi-objective optimization algorithms. A specific instance of this approach is the proposed Fitness-Distance-Ratio Archive-Based Swarm Optimization algorithm, shown to outperform PSO and three other variants, when applied to high-dimensional neural network training problems.

[Full paper](https://dl.acm.org/doi/abs/10.1145/3377929.3398112)

{{< details "Cite" >}}
```bibtex
@inproceedings{10.1145/3377929.3398112,
author = {Rodrigues, Nishant and Mohan, Chilukuri},
title = {Archive-Based Swarms},
year = {2020},
isbn = {9781450371278},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3377929.3398112},
doi = {10.1145/3377929.3398112},
booktitle = {Proceedings of the 2020 Genetic and 
Evolutionary Computation Conference Companion},
pages = {1460–1467},
numpages = {8},
keywords = {artificial neural networks, fitness-distance ratio, archive, 
swarm intelligence, evolutionary machine learning, 
particle swarm optimization, premature convergence},
location = {Canc\'{u}n, Mexico},
series = {GECCO '20}
}
```
{{< /details >}}
