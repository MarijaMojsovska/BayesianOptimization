# BayesianOptimization
(Final project for the course *Information Theory and Inference*)

Investigating the effects of different acquisition functions, Gaussian Process parameters and objective function dimensionality.
Exploring two approaches regarding the GP parameters:
1) maximization of the posterior distribution (frequentist approach);
2) sample from the posterior using Metropolis-Hasting algorithm and marginalize the acquisition function over the GP parameters exploiting the Monte Carlo method (fully-bayesian approach)
   
Bayesian Multi-Scale Optimistic Optimization (BaMSOO): Combines elements of BO and tree based simultaneous optimistic optimization (SOO) to eliminate the need for auxiliary optimization of acquisition functions.
