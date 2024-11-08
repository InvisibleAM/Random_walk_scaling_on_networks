# Random_walk_scaling_on_networks

## Overview
This project implements a Markov Chain scaling analysis in Python, focusing on the computation of path probabilities and their scaling behaviors. The analysis includes polynomial and exponential scaling methods. This was implemented as a course project for the courese PH5490 at IIT Madras. Link to the refered paper is: https://www.nature.com/articles/ncomms6121
## Key Features
- Path Checking: Utilizes breadth-first search (BFS) to identify paths from the start state to the target state.
- Node Filtering: Removes nodes that are not involved in the identified paths.
- Graph Analysis: Identifies strongly connected components and classifies them as acyclic, monocyclic, or multicyclic.
## Scaling Types
- Polynomial Scaling: This method computes the growth of paths in polynomial terms.
- Exponential Scaling: This method analyzes the growth of paths in exponential terms.
## Python Packages Used
- NumPy: For numerical operations and handling arrays.
- SciPy: For sparse matrix operations and linear algebra.
- NetworkX: For graph-based computations and pathfinding.
- Matplotlib: For visualizing results through plots.
## Example Usage
To use this implementation, you can define a transition matrix for a simple Markov chain and specify start and target states. The scaling analysis can then be computed based on these parameters.
