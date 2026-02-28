# Linear Programming: Simplex Method Solver

## 📌 Project Overview
This project features a Python-based implementation of the **Simplex Algorithm**, a popular method for solving linear programming problems (LPP). The solver is designed to find the optimal solution (maximization) for objective functions subject to a set of linear inequality constraints.

## 🧮 Mathematical Approach
The solver processes problems in their **standard form**:
* **Objective Function**: Maximize $Z = c_1x_1 + c_2x_2 + ... + c_nx_n$
* **Constraints**: $Ax \le b$, where $x \ge 0$

The algorithm utilizes:
1. **Slack Variables**: To convert inequalities into equalities.
2. **Initial Tableau**: Constructing the starting matrix for the iterative process.
3. **Pivoting**: Systematically selecting entering and leaving variables based on the optimality condition and the ratio test.
4. **Optimality Check**: Iterating until no further improvements to the objective function can be made.

## 🚀 Key Features
* **Step-by-Step Execution**: The Jupyter Notebook format allows for a clear, cell-by-cell walkthrough of the optimization process.
* **Tableau Visualization**: Displays the transformation of the simplex tableau at each iteration.
* **Optimization Logic**: Handles the identification of pivot rows and columns to find the basic feasible solution.
* **Python-Powered**: Utilizes `numpy` for efficient matrix operations and linear algebra.

## 📂 File Structure
* `Simplex.ipynb` – The primary Jupyter Notebook containing the algorithm implementation, logic, and example problems.

## 🛠 Setup and Usage
1. **Requirements**: Ensure you have Python and Jupyter installed (via Anaconda or pip).
2. **Dependencies**:
   ```bash
   pip install numpy
   pip install matplotlib
