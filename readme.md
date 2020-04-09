# Genetic Algorithm for shortest path problem
## by Sertaç Özker


In this code I will write an example of a genetic algorithm that tries to get from point (0,0) to (1000,0) in 10 steps.

* Each individual can go 100 unit at most on one direction at each step. So, the shortest path is taking 100 units on the x axis on each 10 step without moving in y axis. However, this is very unlikely to achieve.
* At each generation, most successful 100 individual is selected for mating in the next generation.
* When creating a new generation, each indiviauls x and y move on each step is randomly passed to the new generation. However, there is a 10% mutation rate for any random number.
* Each individuals' success is calculated by its distance to the target (1000,0) point at the end of 10 steps. Additionally, it's moves on y axis are added to this distance. So a successful individual should go far on the x axis, without moving much on the y axis.
