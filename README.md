# Genetic Algorithm, Simulated Annealing, and Hill Climbing for Cutting Stock Problem

## Overview
This repository contains the implementation of three robust algorithms: Genetic Algorithm, Simulated Annealing, and Hill Climbing, aimed at solving the NP-hard Cutting Stock Problem (CSP). This project was developed as part of an Artificial Intelligence course and demonstrates the application of these algorithms in optimizing resource usage and minimizing waste. The specific requirements of this project are detailed in the problem statement pdf, which is also a part of this repository.

## Cutting Stock Problem Statement
The Cutting Stock Problem involves efficiently cutting stock materials (like roll paper or sheet metal) into specific sizes based on customer requests while minimizing wastage. This computational problem is recognized as NP-hard due to its complexity.

## Algorithms Implemented
### I. Genetic Algorithm
This implementation of the Genetic Algorithm includes:

Chromosome Representation: Permutation Encoding
Initial Population: Random Initialization
Fitness Function: Amount of Wastage
Parent Selection: Tournament Selection
Recombination: Order Crossover (OX)
Mutation: Scramble Mutation
Replacement: Steady-State Replacement with Elitism

### II. Simulated Annealing
This implementation uses the same kind of permutation encoding used in the genetic algorithm's implementation, and it follows the same standard procedure of creating a simulated annealing algorithm using a decreasing temperature for determining the transition probabilities.

### III. Hill Climbing
The hill climbing implemented here is a simple hill-climbing algorithm that searches for the first instance of a neighbor with a lower cost to move into.

## Features
**Comparative Analysis:** Each algorithm's performance is evaluated against the same set of inputs for a fair comparison.

**Visualization:** Includes plots for learning curves and results to better understand algorithm performance.

**Modular Code:** Easy to understand and modify for further experimentation.

