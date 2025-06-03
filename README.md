# Optimization Project: Steepest Descent Algorithm Implementation

## Introduction

 Optimization plays a fundamental role in mathematics, engineering, machine learning, and many other disciplines that deal with performing iterative procedures that are applied to minimize or maximize a given function based on gradually improving solutions. 

## Overview

This project includes the implementation of the **Steepest Descent Optimization Method** applied to two well-known benchmark functions: **Rosenbrock's Function** and **Himmelblau's Function**. The project aims to explore the behavior and performance of the steepest descent algorithm under different conditions, specifically by varying the step size (constant vs. non-constant Armijo's rule) and initial starting points. The main objective is to minimize these non-linear, differentiable scalar functions iteratively by moving in the opposite direction of their gradients, analyzing the convergence characteristics, computational efficiency, and sensitivity to initial conditions.

 ## Function Definitions
 
1.  **Rosenbrock's Function:**
    $f(x_1, x_2) = (1 - x_1)^2 + 100(x_2 - x_1^2)^2$
    * **Gradient:**
        $\\frac{\\partial f}{\\partial x_1}(x_1, x_2) = -2(1 - x_1) - 400x_1(x_2 - x_1^2)$
        $\\frac{\\partial f}{\\partial x_2}(x_1, x_2) = 200(x_2 - x_1^2)$

2.  **Himmelblau's Function:**
    $g(x_1, x_2) = (x_1^2 + x_2 - 11)^2 + (x_1 + x_2^2 - 7)^2$
    * **Gradient:**
        $\\frac{\\partial g}{\\partial x_1}(x_1, x_2) = 4x_1(x_1^2 + x_2 - 11) + 2(x_1 + x_2^2 - 7)$
        $\\frac{\\partial g}{\\partial x_2}(x_1, x_2) = 2(x_1^2 + x_2 - 11) + 4x_2(x_1 + x_2^2 - 7)$

The minimization is performed using the Steepest Descent method with two different starting points for each function:
* $x_0 = (0, 0)^\\top$
* $\\tilde{x}_0 = (\\pi + 1, \\pi - 1)^\\top$





 
