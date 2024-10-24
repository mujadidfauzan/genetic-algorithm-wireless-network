# Genetic Algorithm Implementation for Wireless Sensor Network Optimization in Surabaya
## Description
This project implements a genetic algorithm to optimize the deployment of wireless sensor networks (WSNs) in the city of Surabaya. The goal is to improve energy efficiency and expand network coverage by determining the optimal placement of towers based on user satisfaction levels, construction costs, and maintenance costs. By analyzing population density data, the genetic algorithm enhances the capabilities of the WSN, providing sustainable solutions for energy management and better service coverage.

## Features
- Utilization of a genetic algorithm for optimization
- Configuration of tower construction and maintenance costs
- Assessment of user satisfaction levels and scores
- Detailed logging of the optimization process and results
- Output of best solutions found during the optimization process

## How It Works
1. **Configuration and Data Loading**:
   - The project reads configuration parameters from a file, including tower costs and user satisfaction levels.
   - It also reads mapping data related to the population density of Surabaya.

2. **Initialization**:
   - The algorithm initializes parameters like population size, mutation probability, and recombination probability.

3. **Genetic Algorithm Execution**:
   - The genetic algorithm runs for a predefined number of iterations (`n_iter`), evolving solutions by selecting, recombining, and mutating tower placements to maximize user satisfaction and minimize costs.

4. **Result Evaluation**:
   - After running the algorithm, it evaluates the best solutions based on fitness, total tower cost, and user satisfaction scores.

5. **Logging and Output**:
   - The results, including the best fitness score, number of towers used, total price, and user satisfaction, are printed and logged for analysis.

## Components
- `main.py`: Main script for running the genetic algorithm and optimizing WSN deployment.
- `problem_config.txt`: Configuration file containing parameters for the problem.
- `maping.csv`: Mapping data for population density in Surabaya.
- `histories.csv`: Output file storing the optimization history.
