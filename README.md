# Evolutionary Optimization with Genetic Algorithms

This project explores the use of evolutionary optimization and genetic algorithms to solve complex mathematical optimization problems.

The project implements and compares multiple evolutionary optimization strategies using custom fitness functions, adaptive mutation techniques, crossover methods, elitism, and tournament selection.

---

## Overview

Evolutionary Optimization is inspired by biological evolution and natural selection.  
The goal is to iteratively improve populations of candidate solutions in order to reach optimal or near-optimal results.

This project focuses on:
- Genetic Algorithms (GA)
- Mutation and crossover strategies
- Optimization of difficult benchmark functions
- Exploration vs exploitation balancing
- Convergence analysis

Two separate implementations were developed and experimentally compared.

---

## Features

- Custom Genetic Algorithm implementations
- Tournament Selection
- Uniform Crossover
- Single-Point Crossover
- Dynamic Mutation Rates
- Elitism
- Adaptive Stagnation Handling
- Fitness Tracking
- Performance Visualization
- Comparative Analysis

---

## Fitness Functions

The project evaluates multiple benchmark optimization functions including:

### Dixon-Price Function
A difficult optimization function with sequential variable dependencies.

### Schwefel + YOU Function
A modified Schwefel function with a custom offset added to the objective function.

### Ackley Function
A highly multimodal benchmark optimization function with many local minima.

---

## Technologies Used

- Python
- NumPy
- Matplotlib
- Genetic Algorithms
- Evolutionary Optimization
- Data Visualization

---

## Optimization Techniques

### Selection Methods
- Tournament Selection
- Roulette Wheel Selection (comparison)

### Crossover Methods
- Single-Point Crossover
- Uniform Crossover

### Mutation
- Dynamic mutation rates
- Non-uniform mutation
- Adaptive mutation strategies

### Elitism
Elite individuals are preserved between generations to maintain high-performing solutions.

---

## Experimental Configuration

| Parameter | Implementation 1 | Implementation 2 |
|---|---|---|
| Population Size | 400 | 400 |
| Genes | 20 | 20 |
| Generations | 1000 | 800 |
| Crossover Rate | 0.6 | 0.8 |
| Mutation Strategy | Dynamic | Dynamic |
| Search Space | (-10,10) | (-500,500) |

---

## Results

### Implementation 1
- Faster convergence
- Lower variance
- Better precision-focused optimization
- Strong exploitation capability

### Implementation 2
- Better exploration
- Higher diversity
- More computationally expensive
- Better large search-space handling

---

## Key Findings

- Balanced mutation rates significantly improve optimization quality
- Excessively high mutation rates reduce convergence quality
- Tournament selection provided better performance than roulette wheel selection
- Uniform crossover improved exploration
- Single-point crossover improved structured exploitation

---

## Visualizations

The project includes:
- Convergence graphs
- Mutation rate comparisons
- Performance comparison charts
- Distribution graphs
- Crossover comparison graphs
- Algorithmic comparison tables

---

## Project Structure

```bash
evolutionary-optimization/
│
├── src/
├── graphs/
├── results/
├── report/
├── main.py
├── requirements.txt
└── README.md
```

---

## Installation

Clone the repository:

```bash
git clone https://github.com/UtkuDemirel07/evolutionary-optimization.git
cd evolutionary-optimization
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Run the Project

```bash
python main.py
```

---

## Academic Context

This project was developed as part of an academic study on evolutionary computation and optimization algorithms.

The work investigates how different genetic algorithm configurations influence convergence speed, robustness, diversity, and optimization quality.

---

## Future Improvements

- Parallelized genetic algorithms
- Hybrid GA + PSO systems
- GPU acceleration
- Multi-objective optimization
- Reinforcement learning integration
- Adaptive crossover mechanisms

---

## Author

Ahmet Utku Demirel

---

## License

This project is for educational and portfolio purposes.
