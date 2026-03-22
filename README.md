# Modeling and Simulation of Aerospace Systems 🛰️📉

[![Simulation](https://img.shields.io/badge/Simulation-MATLAB-orange.svg)](https://www.mathworks.com/products/matlab.html)
[![Modeling](https://img.shields.io/badge/Modeling-Simscape-blue.svg)](https://www.mathworks.com/products/simscape.html)
[![Academic](https://img.shields.io/badge/University-Politecnico%20di%20Milano-blue.svg)](https://www.polimi.it/)

A comprehensive collection of mathematical modeling and numerical simulation projects focusing on aerospace applications. 

Developed for the **Modeling and Simulation of Aerospace Systems (MSAS)** course at Politecnico di Milano (A.A. 2024-2025).

---

## 📌 Project Overview

This repository demonstrates the ability to bridge the gap between pure mathematical theory and applied engineering simulations. It covers the development of custom numerical solvers from scratch and the multi-domain physical modeling of complex spacecraft systems.

The repository is divided into two main assignments:

### 🧮 Assignment 1: Numerical Simulation & Solvers
Focused on solving implicit equations and Initial Value Problems (IVPs) without relying entirely on commercial black-box solvers.
* **Kinematic Analysis:** Solving Freudenstein's equation for a 4-bar linkage kinematic chain using a custom-built multi-dimensional **Newton-Raphson solver**.
* **Aerodynamic Free-Fall:** Simulating the trajectory of a sphere falling through the atmosphere subject to aerodynamic drag.
* **Solver Implementation & Stability:** Writing custom **Forward Euler** and **Runge-Kutta 4 (RK4)** integration schemes. Evaluating their numerical stability, step-size ($h$) sensitivity, and truncation errors by benchmarking them against MATLAB's native `ode45`.

### 🛰️ Assignment 2: Multi-Domain Physical Modeling
Focused on the coupled electro-thermo-mechanical modeling of a satellite's active thermal control system.
* **System Architecture:** A satellite body equipped with fixed solar panels and extendable thermal radiators driven by a DC motor.
* **Electro-Mechanical Modeling:** Formulating the electrical and mechanical differential equations governing the DC motor and the radiator deployment hinge mechanisms.
* **Thermal Control Logic:** Implementing an active logic controller to maintain the satellite's internal temperature within strict operational limits ($[T_{min}, T_{max}]$).
* **Simscape vs. MATLAB:** Comparing a purely script-based mathematical state-space model against a physical network approach built in **Simscape**, validating thrust and drag profiles across steady-state and transient operations.

## 📂 Repository Contents

* **`docs/`**: Contains the detailed academic reports for both assignments, illustrating the analytical formulations, system block diagrams, and numerical error analyses.
* **`src/`** *(Coming soon)*: Will contain the MATLAB scripts, custom ODE solver functions, and the Simscape block-diagram models.

## 👨‍💻 Author

* **Alejandro Rivera Míguez**

---

Professor: **Alessandro Morselli**  
Master in Aeronautical Engineering | Politecnico di Milano

---
*Disclaimer: This is an academic project. The code and models provided are intended for educational demonstration of numerical methods and multi-body aerospace system modeling.*
