# Traveling Salesman Problem (TSP) Solver

This project implements a TSP solver using Branch and Bound in Python.

## Features
- Finds the shortest route visiting all cities
- Visualizes the route using matplotlib
- Pure Python implementation, no external solver required

## Usage
```python
from tsp_branch_and_bound import TSP, plot_tsp

cities = [(0,0), (1,3), (4,3), (6,1), (3,0)]
dist = [[...]]  # distance matrix
TSP(dist)
plot_tsp(cities, final_path)
