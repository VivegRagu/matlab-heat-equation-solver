# matlab-heat-equation-solver
Numerical solution of 1D time-dependent heat equation in MATLAB using finite difference method. Includes solver implementation, 2D/3D visualization, and analysis of temperature distribution in metal rods.
# 🔥 MATLAB Heat Equation Solver

## 📊 Project Overview
A MATLAB implementation for numerically solving the one-dimensional time-dependent heat equation using finite difference methods. This project computes and visualizes temperature distribution in a thin metal rod over time.

## 🧮 Mathematical Background
The heat equation is described by:

\[
\frac{\partial u}{\partial t} = c \frac{\partial^2 u}{\partial x^2}
\]

**Boundary Conditions:**
- Dirichlet boundary: \( u(0,t) = u(L,t) = 0 \)
- Initial condition: \( u(x,0) = f(x) \)

**Parameters:**
- \( u(x,t) \): Temperature at position \( x \) and time \( t \)
- \( c \): Material constant (thermal diffusivity)
- \( L \): Length of the rod
- \( f(x) \): Initial temperature distribution

## ✨ Features
- **Finite Difference Solver**: Numerical solution of 1D heat equation
- **Multiple Visualization**: 2D and 3D plots of temperature distribution
- **Parameter Analysis**: Study of different initial conditions and parameters
- **Performance Testing**: Analysis of numerical stability and convergence
- **Educational Tool**: Clear implementation for learning PDE numerical methods

## 📁 Project Structure
