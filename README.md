Experiment 10: Solution of Ordinary Differential Equations
Overview:

This experiment focuses on solving ordinary differential equations (ODEs) using Euler’s Method in MATLAB. The objective is to understand how numerical techniques approximate solutions over a given interval and to analyze their accuracy.

Methodology:
Given ODE: y′=4e0.8t−0.5y with initial condition y(0)=2
Defined interval: t=0 to 4 with step size h=1
Implementation of Euler’s Method:
Iterative formula: yi+1=yi+f(t,y)⋅h

MATLAB used for:
Step-wise computation
Tabular output generation
Plotting solution curve

Results:
Numerical solution successfully computed over the interval
Observed accumulation of error with each step
Approximate error reached ~24% at t=4
Method provided a simple but less accurate approximation
Identified need for higher-order methods (Modified Euler, Runge-Kutta) for better accuracy
