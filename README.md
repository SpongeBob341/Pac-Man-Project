# Pac-Man-Project

## Project 1
I implemented depth-first, breadth-first, uniform cost, and A* search algorithms. These algorithms are used to solve navigation and traveling salesman problems in the Pacman world.

## Project 2
Classic Pacman is modeled as both an adversarial and a stochastic search problem. I implemented multiagent minimax and expectimax algorithms, as well as designed evaluation functions.

## Project 3
In this project, I have used simple Python functions that generate logical sentences describing Pacman physics, aka pacphysics. Then used a SAT solver, pycosat, to solve the logical inference tasks associated with planning 

## Project 4
I implemented a tracking algorithm which maintains a belief state for each ghost being tracked. Belief states are updated with each observation and with each time lapse.
Sometimes the state space is too large to store. I implemented approximate inference with a joint particle filter algorithm. Each ghost action is influenced by the positions of the other ghosts, so resampling required querying a provided Bayes Net which describes the ghosts' transition function.
