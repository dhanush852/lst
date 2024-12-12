# Speed Control of a DC Motor Using PID and LQR Controllers

## Overview
This project demonstrates the implementation of speed control for a DC motor using Proportional-Integral-Derivative (PID) and Linear Quadratic Regulator (LQR) control strategies. MATLAB and Simulink are utilized to model, simulate, and validate the system's performance under various conditions.

## Files Included
1. **`Speed_Control_of_DC_motor.slx`**
   - Simulink model for DC motor speed control.
   - Includes DC motor dynamics, PID controller, and LQR controller implementations.
   - Use this file to simulate and visualize motor behavior with different control strategies.

2. **`lst_lqr_testing1.m`**
   - MATLAB script for testing and analyzing the LQR controller.
   - Contains code for state-space representation, optimal gain calculation, and system response evaluation.

## Requirements
- **MATLAB**: Version R2020a or later is recommended.
- **Simulink**: Ensure compatibility with the MATLAB version.

## How to Run

### Simulink Model
1. Open `Speed_Control_of_DC_motor.slx` in Simulink.
2. Click on the **Run** button to start the simulation.
3. Observe the performance metrics, such as rise time, overshoot, and settling time, in the simulation output.

### MATLAB Script
1. Open `lst_lqr_testing1.m` in MATLAB.
2. Run the script to test the LQR controller:
   ```matlab
   run('lst_lqr_testing1.m')

