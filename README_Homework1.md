# Spring Network Simulation

This repository contains the implementation and report for **Homework 1** (Spring Network Simulation).  

Homework_1 Includes these different Functions:

    gradEs.py # Computes gradient (force contribution) of spring stretching energy
    hessEs.py # Computes Hessian (Jacobian contribution) of a spring
    getFexternal.py # Computes external forces (e.g., gravity)
    getForceJacobian.py # Assembles residual forces and Jacobian matrix
    myInt.py # Implicit integrator with Newton–Raphson iterations
    plot.py # Visualizes spring network configurations
    nodes.txt Document With the Physical Starting location of the nodes with the first and last nodes fixed
    springs.txt is a documet noting to which nodes the springs are attached to and the spring constant for each spring

Homework1_Lee.tex # LaTeX report with explanations, results, and figures

To Run the Homework_1 code open the code in google colab and press run all at the top to display results.
  To change the nunber of nodes / springs or their configuration change the nodes.txt file and the springs.txt file with the 
  knowlege that the first and last nodes in the document are fixed and will not change over time.
