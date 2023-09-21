# Intelligent Agents Library
### Assignments part of CS7320 Artificial Intelligent by Dr. Michael Hahsler

### Intelligent agent that navigates and cleans a room
Intelligent agents of varying degrees of sophistication traverse an environment (2D array) to vacuum "dirty" squares and their performances are compared and analyzed 

**Agent Types**
- randomized agent: every movement is randomized and will not react to "walls" and "obstacles" and can continue to bump into the same wall
- simple reflex agent: movement is randomized but will react to "obstacles" and "walls" and redirect itself
- model based agent: uses *states* to keep track of current location and previously visited squares and uses this knowledge for navigation

### Intelligent agent that solves the n-queens problem
n-queens problem deals with finding an arrangement of n queens on a n x n chess board so that no queen is on the same row, column, or diagonal as any other queen.

This problem can be solved with many different algorithmic techniques, but in this demonstration we use different variations of hill-climbing algorithms as well as simulated annealing and compare and perform analysis.

**algorithms used**
- steepest-ascend hill climbing search
- stochastic hill climbing
- stochastic hill climbing -- first-choice variation
- hill climbing with random restarts (to avoid getting stuck on local optima)
- simulated annealing

### Intelligent agent that navigates a maze through various algorithms
The goal-based agent uses different algorithms to solve a maze represented as a 2D array:

```
XXXXXXXXXXXXXXXXXXXXXX
X XX        X X      X
X    XXXXXX X XXXXXX X
XXXXXX     S  X      X
X    X XXXXXX XX XXXXX
X XXXX X         X   X
X        XXX XXX   X X
XXXXXXXXXX    XXXXXX X
XG         XX        X
XXXXXXXXXXXXXXXXXXXXXX
```

where "S" and "G" mark the start and goal respectively and "X" marks walls.

**Algorithms used**
- Breadth First Search (BFS)
- Depth First Search (DFS)
- Greedy best-first search (GBFS)
- A-star search
- Iterative Deepening Search