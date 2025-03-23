# 2024-03-Perturbative-Techniques

This project, developed with Pietro de Checchi, explores different Perturbative Techniques to analyze the dynamics of Duffing pendulum:
```math
\ddot{\theta}=-\omega_0^2 (1 + \varepsilon \cos(\omega t))\sin(\theta)
```
The implementation is performed in ```Mathematica```. 

The project includes:
- *"Project1A_Lindstedt_elliptic"* - The Lindstedt Method for the Duffing pendulum, around an elliptic equilibrium $(0,0)$ 
- *"Project1B_Lindstedt_hyperbolic"* - The Lindstedt Method for the Duffing pendulum, around a hyperbolic equilibrium $(\pi,0)$ 
- *"Project1C_Lindstedt_damping"* - The Lindstedt Method for the Duffing pendulum, around an elliptic equilibrium and with damping
- *"Project2A_PoincareDulac_ord2"* - The Poincaré-Dulac Normal Form Method for the Duffing pendulum, up to order two
- *"Project2A_PoincareDulac_ord3"* - The Poincaré-Dulac Normal Form Method for the Duffing pendulum, up to order three
- *"Project2B_PolynomialSubstitution"* - Code for efficient polynomial substitution in ```Mathematica```, then used in the Poincaré-Dulac Normal Form codes. 

