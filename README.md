# 0/1 Knapsack Problem

In this repository, the files are organised as follows:
- .ipynb file is the Jypyter notebook containing the source code.
- .csv file is the input data of the 0/1 knapsack problem.
- Asessment Brief.pdf contains the requirement of the problem.
- report.pdf is the formal report detailing my implementation of the algorithms (Simulated Annealing and Tabu Search), the results of the  testing with analysis, and a formal conclusion. 

Simulated Annealing and Tabu Search are selected to solve the 0-1 knapsack problem because they are metaheuristics that can either avoid or escape the local optima. There are many of real-life applications of the knapsack problem.

For the chosen parameters, Simulated Annealing achieved an average total value of packing in 10 runs of 4413.6, while Tabu Search achieved that of 4378.0. In terms of the mentioned metric, Simulated Annealing is slightly better than Tabu Search. 

However, Simulated Annealing is a stochastic algorithm and Tabu Search is, on the other hand, a deterministic algorithm. The performance (total value of packing in each run) of Tabu Search is more stable than that of Simulated Annealing. 

In the future, further tuning and trials of parameters can be performed for the current Simulated Annealing and Tabu Search Algorithms. 

Parallelised Simulated Annealing algorithm and Quantum Inspired Tabu Search can be applied and implemented on 0-1 knapsack problem.

