Project Overview：

This project implements a Learning Model Predictive Control (MPC) system for controlling vehicle dynamics, with a focus on addressing uncertainties in autonomous driving. The project integrates Gaussian Process (GP) for state prediction and uncertainty management with MPC to optimize vehicle control and trajectory tracking. The system is designed to handle complex driving scenarios and improve robustness in the face of dynamic changes and uncertainties.

Key Features：

Gaussian Process (GP) Integration: Uses GP for predicting vehicle state and uncertainty.
Model Predictive Control (MPC): Optimizes control actions to minimize trajectory tracking error while considering constraints.
Dynamic Vehicle Model: Implements a bicycle model for vehicle dynamics with support for complex environments and obstacles.
Optimization: Utilizes IPOPT for parameter tuning and constraint satisfaction.
Simulation and Analysis: Provides tools for simulating vehicle behavior and analyzing performance under different conditions.

Project Structure：

gp_class.py: Implements the Gaussian Process model for vehicle state prediction and uncertainty quantification.
mpc_class.py: Implements the Model Predictive Control algorithm, optimizing control actions to minimize trajectory tracking error.
model_class.py: Contains the vehicle dynamics model (bicycle model) used for state prediction and control.
optimize.py: Optimization functions using IPOPT for hyperparameter tuning and system performance optimization.
car_example.py: Example script to simulate the vehicle’s motion in a given environment and demonstrate the integration of GP and MPC.
gp_functions.py: Supporting functions for GP training, prediction, and performance evaluation.
