This research assignment aims to compare three algorithms on their performance on a global optimisation search within the drop-wave function. The three algorithms that will be tested are:

Steepest Descent (SD)(Cauchy)
Conjugate Direction (CD)
Particle Swarm
The purpose of this comparison is to highlight the issue of needing an initial starting position for optimisation algorithms when looking to optimise over a complex geometric plane. The drop-wave function is a function with many steep hills and valley's, making it a good test for algorithms designed to find the global minima. However, due to these steep hills and valley's, the performance of the SD and CD algorithms becomes highly dependent upon their starting position. This is highlighted on both algorithms through a series of tests using different starting points.

This issue is overcome in two-ways:
Firstly, by using latin hypercube sampling to generate intitial starting position, effectively running each algorithm multiple times and taking the lowest value to be the global minima.
Secondly, by using an algorithm that doesn't rely on an intital starting position. We use the Particle Swarm Optimisation (PSO). This algorithm does not depend on a specific intitial starting position nor does it rely on differentiation.

A comparison is done on the performance of each:

Steepest Descent (SD) with Latin Hypercube Sampling
Conjugate Direction (CD) with Latin Hypercube Sampling
Particale Swarm Optimisation (PSO)
They are compared on the basis of computational efficiency & accuracy.
