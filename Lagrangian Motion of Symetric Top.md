# Symmetric Top Motion Analysis

This Python script demonstrates the calculation and visualization of the motion of a symmetric top. It uses numerical integration techniques to solve the equations of motion for a symmetric top and provides insights into its behavior. The symmetric top consists of a spinning body with axial symmetry, and its motion is governed by the conservation of angular momentum and energy.

# System Description

The system is described by the following parameters:

L: Distance from the center of mass to the tip of the top (in meters).
M: Mass of the top (in kilograms).
g: Gravitational acceleration (in m/s²).
beta: Parameter that sets the moments of inertia (used to calculate I1 and I3).
I1: First principal moment of inertia.
I3: Moment of inertia about the symmetry axis.

# Equations of Motion

The Lagrangian for the system is given, and it leads to the following Lagrange equations:

Equations of motion for $\theta$, $\dot{\theta}$, $\phi$, and $\psi$.
Conservation of generalized momenta for $p_\phi$ and $p_\psi$.
The energy is also conserved and can be expressed in terms of kinetic and potential energy.

# Numerical Integration

The script uses the odeint function from the SciPy library to numerically integrate the equations of motion over a specified time interval. It calculates the motion of the symmetric top based on initial conditions for angles and angular velocities.

# Energy and Effective Potential

The script calculates and plots the effective potential energy function, which helps identify turning points in the nutation (tipping) motion. It also calculates and verifies the conservation of energy throughout the motion.

# Visualization

The motion of the symmetric top is visualized in the following ways:

Plotting the nutation (tipping) angle $\theta$ over time.
Plotting the precession angle $\phi$ over time.
Generating a 3D trajectory of the center of mass of the top.
Creating an animation of the top's motion and saving it as an MP4 file.

# Usage

To use this script:

Modify the system parameters and initial conditions to suit your scenario.
Run the script to calculate and visualize the motion of the symmetric top.
View the animation to observe the top's behavior.
Note: This script assumes that you have the required Python libraries (SciPy, NumPy, Matplotlib) installed in your environment.

Enjoy exploring the motion of the symmetric top!

Most credit goes to my physics professor Robert Johnson for teaching me the beauty of lagrangian mechanics.