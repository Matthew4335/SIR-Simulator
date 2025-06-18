# SIR-Simulator

A comprehensive infectious disease modeling simulator implementing the SIR (Susceptible-Infected-Recovered) epidemiological model with mathematical analysis, numerical simulations, and interactive visualizations.

## Description

The SIR-Simulator is an educational and research tool for understanding infectious disease dynamics through mathematical modeling. It implements the classic SIR model, which divides a population into three compartments:

- **S (Susceptible)**: Individuals who can contract the disease
- **I (Infected)**: Individuals currently infected and capable of spreading the disease
- **R (Recovered)**: Individuals who have recovered and gained immunity

This project is designed for:
- **Students** learning about mathematical epidemiology
- **Researchers** studying disease transmission dynamics
- **Educators** teaching mathematical modeling concepts
- **Anyone interested** in understanding how infectious diseases spread through populations

The simulator provides both theoretical analysis (phase portraits, stability analysis) and practical numerical simulations with customizable parameters.

## Features

### 🔬 Mathematical Analysis
- **Phase Portrait Visualization**: Interactive stream plots showing disease dynamics
- **Stability Analysis**: Fixed point analysis with Jacobian matrices
- **Parameter Sensitivity**: Contour plots showing how parameters affect disease spread

### 📊 Numerical Simulations
- **ODE Solver Integration**: Uses SciPy's `solve_ivp` for accurate numerical solutions
- **Customizable Parameters**: Adjustable transmission rate (τ) and recovery rate (κ)
- **Multiple Scenarios**: Compare different disease parameters side-by-side
- **Stopping Conditions**: Automatic simulation termination when infection levels drop below thresholds

### 📈 Visualization
- **Time Series Plots**: Track S, I, R populations over time
- **Phase Space Analysis**: Visualize system dynamics in state space
- **Parameter Space Exploration**: Contour plots for parameter sensitivity analysis

### 🎯 Educational Tools
- **Jupyter Notebook**: Interactive environment with explanations and code
- **Python Script**: Standalone implementation for batch processing
- **Mathematical Documentation**: Detailed explanations of model derivations

## Tech Stack

### Core Technologies
- **Python 3.x**: Primary programming language
- **NumPy**: Numerical computing and array operations
- **SciPy**: Scientific computing, particularly ODE solving
- **Matplotlib**: Data visualization and plotting
- **Pylab**: Additional plotting utilities

### Development Environment
- **Jupyter Notebook**: Interactive development and documentation
- **Google Colab**: Cloud-based execution environment
- **Markdown**: Documentation formatting

### Mathematical Libraries
- **SciPy.integrate**: Ordinary differential equation solvers
- **NumPy.linalg**: Linear algebra operations for stability analysis
- **Matplotlib.pyplot**: Advanced plotting capabilities
