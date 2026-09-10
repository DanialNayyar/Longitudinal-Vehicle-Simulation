# Longitudinal-Vehicle-Simulation & Gear Shift Optimisation

A first principles Python model of longitudinal vehicle performance and gear shift optimisation.

## Overview
The model combines:
- Engine torque and power curves
- Six speed drivetrain and modelling of tractive force
- Modelling of aerodynamic drag and rolling resistance
- Gear shift optimisation based on adjacent gear tractive force curves

## Results

- 0-200 km/h, redline strategy: **18.90 s**
- 0-200 km/h, optimised strategy: **17.12 s**
- Improvement: **9.42%**
- Top speed reached (Target of 350 km/h): **Optimised = 267 km/h vs Redline = 250 km/h**


The model used synthetic vehicle and engine parameters to demonstrate the modelling and optimisation methodology.


## Tools
Python (NumPy, Matplotlib)

## Report
A small technical report covering the study including the modelling, assumptions and results is in the repository.
