# AIND-SimulatedAnnealing
This is in practice simulated annealing with the Traveling Salesman Problem (TSP)

I implemented the simulated annealing code with help from the pseudocode from Udacity's psuedocode on simulated annealing.

The basic idea is to explore states/nodes until the maximum state (in this case, the minimum as it searches for the greatest negative number) is found. It will use a sort of temperature function to create lots of entropy before finally resting on the nodes that have the minimum distance.

All the code is runnable and the simulations have different results because of the randomness of the simulated annealing function. 

TODO: change the parameters to the function to have a more stable / more accurate result.
