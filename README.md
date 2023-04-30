# AI plays Flappy Bird

> Project_Summary

Flappy Bird is a popular game in which the player navigates through horizontally scrolling pipes by avoiding collision with them along the way. 

This project demonstrates the implementation of NEAT algorithm, which showcases how the algorithm can learn in any environment and exhibit a desired behaviour i.e. navigating the Flappy bird through the course endlessly.


> How_Flappy_bird_implements_NEAT_algorithm?

* The algorithm takes the following INPUTS:
#
    -> Y position of the Player/Bird
    -> Vertical Distance of Player/Bird from Bottom pipe
    -> Vertical Distance of Player/Bird from Top pipe
    -> Horizontal Distance of Player/Bird from Pipe


* The OUTPUT of the algorithm is to take action whether the player is to jump or fall under the influence of gravity.

* With respect to the NEAT algorithm, the fitness of the player is determined by the number of pipes that the player is able to cross without collision. As soon as the player collides with the pipe, hits roof or falls down to the ground, it is removed from the environment.

* The performance of the algorithm depends on the initial population that is taken into consideration. As the members of population compete for survival (based on their maximum score) through the evolving generations, the genomes undergo crossover and mutate continuously until a satisfying behaviour is achieved.


> Advantages of NEAT algorithm:

* NEAT networks learn using a reward function and not back propagation. It executes actions, observes and learns how to behave in a given environment via   reinforcement learning. 
* The implementation of the algorithm does not require any data set, as it can learn by trial and error method by using sensory data perceived from the environment.


>Applications of NEAT algorithm:

It can be used as a solution in:

* Training a robot to balance a pole or operate to perform a certain activity
* Training Self Driving Cars
* Basically training any AI model without any given fixed data set.


