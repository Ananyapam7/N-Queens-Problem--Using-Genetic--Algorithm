# An adaptive Genetic Algorithm for solving the N-Queens-Problem

## Introduction

Optimization problems can be of two types: Unconstrained and Constrained. They involve both continuous as well as discrete variables. The usual non-linear nature of these problems in association with a handful of restraints being active at the global optima make the task of finding the optimal solutions all the more troublesome. Optimization techniques and approaches have been successfully applied to various systems, namely, Stochastic Systems, Trajectory Systems, and Deterministic Systems. Stochastic Systems comprises of the optimal control problem in the presence of uncertainty. Trajectory Systems involves aerial paths but is mostly restricted to the computation of optimum
trajectories of the rockets and space flight trajectories. Deterministic Systems includes the computations of the
performance of several mathematical models of diverse engineering design problems for various physical systems
modelling with germane objective functions. Traditional methods which are used previously to solve these Multiobjective Optimization problems include Gradient Descent, Dynamic Programming and Newton Methods. But they
are not devoid of shortcomings- they are computationally less efficient. 

Then meta-heuristic algorithms came into existence. These meta-heuristic approximate algorithms tend to provide better solutions in a reasonable amount of time. There exists a number of meta-heuristics like Genetic Algorithm (GA), Particle Swarm Optimization (PSO), Gravitational Search Algorithm (GSA), Ant Colony Optimization (ACO), Stimulated Annealing (SA) , Plant Propagation Algorithm (PPA) and so on.

This is a Meta-heuristic approach for solving the N-Queens Problem to find the
best possible solution in a reasonable amount of time. 
This algorithm is studied from [this](https://arxiv.org/abs/1802.02006) abstract and the algorithm is implimented in python.
Genetic Algorithm is used with a novel fitness function as the Meta-heuristic. 

The aim of N-Queens Problem is to place N queens on an N x N chessboard, in a way so
that no queen is in conflict with the others. Chromosome representation and genetic operations like Mutation
and Crossover are described in detail. Results show that this approach yields promising and satisfactory results
in less time compared to that obtained from the previous approaches for several large values of N.

## Acknowledgements

Abstract: [https://arxiv.org/abs/1802.02006](https://arxiv.org/abs/1802.02006)