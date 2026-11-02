# MAE 598: Design Optimization (Arizona State University, 2022)

Coursework and projects from the graduate design optimization course at ASU.

## Projects

**Project 1: Rocket landing trajectory optimization** ([notebook](Project%201/Project%201.ipynb))
Frames rocket landing as a discrete-time optimal control problem (distance, velocity, orientation, angular velocity, drag) and trains a neural-network controller in PyTorch using automatic differentiation.

**Project 2: Brake disc design optimization** ([report](Project%202/Project2.pdf))
Multi-objective optimization of a brake disc in ANSYS: minimizes volume, stress and temperature while raising the first natural frequency, using Latin hypercube DOE, response surfaces, sensitivity analysis and MOGA.

<p align="center"><img src="Project%202/spider.png" width="420" alt="Brake disc design trade-off chart"></p>

## Homework
`Homework/` holds assignments 1–5 (Jupyter notebooks with PDF exports): unconstrained and constrained optimization, gradient methods, and KKT conditions.

## Tools
Python, PyTorch, NumPy, Matplotlib, Jupyter, ANSYS Workbench
