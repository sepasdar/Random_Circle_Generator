# Random_Circle_Generator
This algorithm generates randomly distributed circles within a specified domain based on a target distribution for the circle nearest neighbor distances (NND). The target distribution is chosen to be Weibull although it can be replaced by any distribution.  The similarity between the generated and target distributions is measured using KL-Divergence.
The circles can have different diameters. A minimum clear distance between the circles can be specified so that the circles do not touch or get too close to one another. 

You can find detailed information regarding the algorithm and implimentaiton in Section 4 of this [paper](https://arxiv.org/abs/2104.04485).

If you are interested in this work and use the materials, please cite the following papers:
**Sepasdar, R., Karpatne, A., & Shakiba, M. (2021). A Data-Driven Approach to Full-Field Damage and Failure Pattern Prediction in Microstructure-Dependent Composites using Deep Learning. arXiv preprint arXiv:2104.04485.**
