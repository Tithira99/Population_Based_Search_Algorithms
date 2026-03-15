# Population-Based Search Algorithms for Solving the Traveling Salesman Problem
## Project Overview

This project explores the application of population-based metaheuristic optimization algorithms to solve the Traveling Salesman Problem (TSP), a well-known NP-hard combinatorial optimization problem.

The project was conducted as part of the Introduction to Meta-Heuristics course and implemented using Python in Google Colab.

The objective of the project was to evaluate the effectiveness of Genetic Algorithm (GA) and Ant Colony Optimization (ACO) in solving TSP instances of different sizes while analyzing their solution quality, convergence behavior, and computational performance.

## Problem Description
### Traveling Salesman Problem (TSP)

The Traveling Salesman Problem aims to find the **shortest possible route that visits each city exactly once and returns to the starting city.**

TSP is widely used as a benchmark problem for evaluating optimization algorithms because:

- It is **NP-hard**

- The number of possible solutions grows **factorially with the number of cities**

- Exact solutions become computationally expensive for larger problem sizes

Population-based metaheuristic algorithms such as **GA and ACO** provide effective **approximate solutions for large-scale TSP instances.**

## Algorithms Implemented
### Genetic Algorithm (GA)

The Genetic Algorithm is an evolutionary optimization technique inspired by natural selection.

Key mechanisms implemented include:

- Population initialization

- Fitness evaluation

- Selection

- Crossover

- Mutation

- Iterative evolution of solutions

The algorithm searches for improved routes through iterative evolution of candidate solutions.

### Ant Colony Optimization (ACO)

Ant Colony Optimization is inspired by the foraging behavior of ants, where ants communicate using pheromone trails to discover efficient paths.

Key mechanisms implemented include:

- Pheromone initialization

- Probabilistic path construction

- Pheromone update rules

- Exploration vs exploitation balancing

- Iterative solution improvement

ACO gradually improves routes by reinforcing shorter paths with stronger pheromone trails.

## Experimental Setup

The algorithms were tested on TSP instances with different problem sizes:

- 10 cities

- 50 cities

- 100 cities

The experiments evaluated:

Total tour distance

- Convergence behavior

- Algorithm efficiency

- Solution quality

Visualizations were generated to observe algorithm performance and convergence patterns.

## My Contributions

Although this was a three-member team project, I played a leading role in organizing and coordinating the project.

My responsibilities included:

- Coordinating project activities and organizing team tasks

- Performing parameter optimization for both GA and ACO algorithms

- Implementing and testing algorithm configurations

- Creating visualizations of algorithm performance

- Conducting experiments and analyzing results

- Contributing to the documentation and report preparation

- Preparing presentation materials

## Technologies and Tools

- Python

- Google Colab

- Genetic Algorithm (GA)

- Ant Colony Optimization (ACO)

- Metaheuristic Optimization

- Data Visualization

- Algorithm Performance Analysis

## Learning Outcomes

Through this project, the following key concepts were developed:

- Understanding **population-based metaheuristic algorithms**

- Applying optimization techniques to **NP-hard combinatorial problems**

- Evaluating algorithm performance through **experimental analysis**

- Understanding the effect of **hyperparameter tuning on algorithm performance**

- Collaborating in a **team-based research environment**

## Team Members

- **Tithira Withanaarachchi** – Project coordination, parameter optimization, implementation support, experimentation, documentation, visualization and analysis

- Minnah Aamir – Implementation of Ant Colony Optimization (ACO)

- Kohei Kuwana – Implementation of Genetic Algorithm (GA)

## Course

Introduction to Meta-Heuristics,
University of Aizu
