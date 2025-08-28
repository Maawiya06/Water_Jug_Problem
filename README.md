# Water Jug Problem Solver

This project implements a solution to the classic **Water Jug Problem**, a fundamental search problem in Artificial Intelligence.  

---

## Problem Statement
We are given two jugs with different capacities and must measure out an exact target quantity of water.  
At each step, we can:
- Fill a jug completely
- Empty a jug
- Pour water from one jug into the other until one is empty or the other is full

The goal is to find a sequence of steps that reaches the target amount.

---

## Features
- Implementation in Python using a Jupyter Notebook
- Uses **Breadth-First Search (BFS)** to guarantee the shortest sequence of steps
- Prints the sequence of states leading to the solution
- Easy to extend for any jug capacities and target volume

---

## Example
Suppose we have:
- Jug X capacity = 4 liters  
- Jug Y capacity = 3 liters  
- Target = 2 liters  

The solver finds a valid sequence of steps to measure exactly 2 liters.

---

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/water-jug-solver.git
   cd water-jug-solver
## Output
Initial State: (0, 0)
Fill Jug X: (4, 0)
Pour X -> Y: (1, 3)
Empty Jug Y: (1, 0)
Pour X -> Y: (0, 1)
Fill Jug X: (4, 1)
Pour X -> Y: (2, 3)
Target reached: 2 liters
