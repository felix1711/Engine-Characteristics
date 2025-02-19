Vehicle Dynamics Simulation


Overview
This project simulates vehicle dynamics based on engine, transmission, tire, and road conditions. It models the relationship between engine speed, torque, power, gear ratios, traction, and vehicle speed over time using Python and Matplotlib for visualization.

Features
Defines classes for Engine, Transmission, Tires, Vehicle, and Road Conditions
Simulates vehicle performance over a time range

Plots:
->Engine torque and power curves
->Engine speed, torque, power, engaged gear over time
->Wheel torque, traction force, acceleration, and vehicle speed over time


Dependencies:
Python 3.x
NumPy
Matplotlib

Code Explanation :

Classes
->Engine: Defines engine characteristics such as torque, power, and RPM limits.
->Transmission: Defines gear ratios and efficiency.
->Tire: Includes tire dimensions, friction coefficient, and rolling resistance.
->Vehicle: Defines mass, drag coefficient, and frontal area for aerodynamic effects.
->Road: Defines road slope and rolling resistance.


Visualization:
->Torque and Power Curve: Shows how engine torque and power vary with RPM.
->Time-based Performance Plots: Displays variations in engine speed, torque, power, engaged gear, traction force, acceleration, and vehicle speed.
