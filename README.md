# A parallel Competitive Particle Swarm Optimization for non-linear first arrival traveltime tomography and uncertainty quantification
[![DOI](https://img.shields.io/badge/DOI-10.1016/j.cageo.2018.01.016-blue.svg)](https://doi.org/10.1016/j.cageo.2018.01.016)


## Abstract

Seismic traveltime tomography is an optimization problem that requires large computational efforts. Therefore, linearized techniques are commonly used for their low computational cost. These local optimization methods are likely to get trapped in a local minimum as they critically depend on the initial model. On the other hand, global optimization methods based on MCMC are insensitive to the initial model but turn out to be computationally expensive. Particle Swarm Optimization (PSO) is a rather new global optimization approach with few tuning parameters that has shown excellent convergence rates and is straightforwardly parallelizable, allowing a good distribution of the workload. However, while it can traverse several local minima of the evaluated misfit function, classical implementation of PSO can get trapped in local minima at later iterations as particles inertia dim. We propose a Competitive PSO (CPSO) to help particles to escape from local minima with a simple implementation that improves swarm's diversity. The model space can be sampled by running the optimizer multiple times and by keeping all the models explored by the swarms in the different runs. A traveltime tomography algorithm based on CPSO is successfully applied on a real 3D data set in the context of induced seismicity.

**Keywords** : microseismic, traveltime tomography, particle swarm optimization, uncertainty quantification, high performance computing


![Importance sampling](importance_sampling.png)