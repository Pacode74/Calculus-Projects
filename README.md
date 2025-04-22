## 📁 Calculus Projects Overview

This repository contains two complete Jupyter Notebook projects that apply core concepts from **Calculus AB** to solve and analyze real-world problems:

1. [**Newton’s Law of Cooling – The Potato Problem**](#-newtons-law-of-cooling--the-potato-problem)  
   📄 File: `Potato_Problem_Project.ipynb`

2. [**Optimization Project: Minimizing a Sum of Squares**](#-optimization-project-minimizing-a-sum-of-squares)  
   📄 File: `Minimize_Sum_Square.ipynb`

Each project uses symbolic calculus, Python code, and visualizations to explain and solve the problem step-by-step.

---

## 🥔 Newton’s Law of Cooling – The Potato Problem
### A Calculus Project in a Real-World Context

This project explores Newton’s Law of Cooling through the lens of a famous AP Calculus FRQ often referred to as the “Potato Problem.” We model the internal temperature of a potato cooling in a room and apply key calculus concepts—rates of change, differential equations, approximations, and error analysis.

Through step-by-step analysis, we answer conceptual and computational questions using symbolic math, Python code, and visualizations.

### 🔍 Key Topics Covered

- Define the differential equation for $H'(t)$ (implicit and explicit forms)
- Solve $H'(t) = -\frac{1}{4}(H - 27)$ with initial condition $H(0) = 91$
- Derive the solution: $H(t) = 27 + 64e^{-t/4}$
- Use tangent lines and linear approximation at $t=0$
- Determine concavity and under/overestimation using $H''(t)$
- Plot the second derivative to confirm concavity is always positive
- Identify no inflection points (always concave up)
- Define and compare:
  - Unnormalized accumulation function: $\Delta H(t) = 64(e^{-t/4} - 1)$
  - Normalized accumulation: $F(t) = 1 - e^{-t/4}$
- Determine when $H(t) = 27.01$ using inverse exponential
- Compute:
  - Average value of $H(t)$ over $[0, 35.06]$
  - Average rate of change over same interval
  - Compare and explain difference between average value and average rate
- Create 1st to 5th order Taylor Polynomials
- Evaluate error of each approximation
- Define acceptable error threshold (e.g. 1°C)
- Determine where error exceeds tolerance
- Discuss the role of curvature in approximation quality
- **Optimize cooling strategy**: Minimize time by maximizing $k$ in $H(t) = 27 + 64e^{-kt}$

---

## 📘 Optimization Project: Minimizing a Sum of Squares

### 🔬 Problem Statement
> What is the smallest possible sum of squares of two numbers, given that their product is -16?

This classic problem explores:
- Function minimization under constraint
- Symbolic math and substitution
- Derivative-based critical point analysis
- Visualization of functions and their slopes

### 🎯 Goal
Minimize:
$$
F(x, y) = x^2 + y^2 \quad \text{subject to} \quad xy = -16
$$

Substitute to reduce to one variable:
$$
S(x) = x^2 + \frac{256}{x^2}
$$

Use calculus to:
- Find critical points
- Test using $S'(x)$ and $S''(x)$

### 🛠️ Tools Used
- **SymPy**: symbolic derivatives and solving
- **Pandas**: slope sign charts
- **Matplotlib**: visualize $S(x)$, $S'(x)$, $S''(x)$
- **Inset plots**: zoom on minima near $x=\pm 4$

### 📊 Result
- Minimum sum of squares is $S(x) = 32$
- Occurs at $x = 4 \Rightarrow y = -4$ and $x = -4 \Rightarrow y = 4$

### 📂 How to Run
Open the notebook file `Minimize_Sum_Square.ipynb` and run cells step by step.

### 📖 Learning Outcomes
- Use substitution to minimize multivariable functions
- Apply first and second derivative tests
- Visualize and interpret critical points
- Understand discontinuity issues (e.g. $x = 0$ is undefined)

---

Both projects are presented with clean, readable code and include plots, markdown explanations, and conclusions to illustrate each mathematical result. Great for anyone studying calculus or seeking practical applications of differential equations and optimization.

