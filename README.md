# GENETIC-ALGORITHM

In this project,we address the issue of optimizing distribution of energy in smart grid . The main objective is to determine the most rational ways of distributing the power supplied by various sources (such as Solar and Wind) among the nodes of consumers during 24 hours of the day.
We want to do this in such a way that the costs are minimized, save the energy lost in transmission and satisfy consumer demand as much as possible. 
We have introduced a Genetic Algorithm (GA) in order to address such a complex problem. Parallel computing was another implementation we included as an attempt to get the algorithm to run faster by speeding up the fitness evaluation step, this time by utilizing Python `multiprocessing` library.

> The multi-objective optimization attempts to simultaneously minimize the operation costs, transmission losses and penalties on failing to satisfy the demand and source limits.
> To find good solutions we created a standard GA using functions selection, crossover, and mutation.
> Parallel Computing: We applied `multiprocessing` to compute fitness values of multiple solutions simultaneously in hope to achieve a better performance.
> Constraint Handling: Our fitness function imposes penalties when the capacity of a given source is exceeded, when demand cannot be satisfied and when energy consumption exceeds energy limits at peak periods.
>Visualization:  We compare the performance and speed of our GA (our normal and parallel version) with a more trivial greedy approach.

Note: This assignment is a part of college assignment. 
