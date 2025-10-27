## README: Elastic Beam Simulation

This repository contains Python code to simulate the static and dynamic behavior of an elastic beam under various loads and boundary conditions using a finite element approach.

### How to Run the Code

1.  **Open the Jupyter Notebook:** Open the `Homework2' notebook in a Jupyter environment.
2.  **Run All Cells:** Execute all the code cells in the notebook sequentially. The notebook is structured to define helper functions first, followed by the main simulation loop and plotting.
3.  **Adjust Parameters:** Modify the parameters in the "Main" section (e.g., `nv`, `dt`, `totalTime`, `RodLength`, `R_outer`, `R_inner`, `Y`, `visc`, `point_load_magnitude`) to explore different scenarios.
4.  **Modify Boundary Conditions:** Adjust the `fixed_index` array in the "Boundary Conditions" section to change the fixed degrees of freedom.
5.  **Analyze Results:** The notebook will output plots showing the beam's deflection over time and a comparison of simulated maximum deflection with theoretical Euler-Bernoulli beam theory predictions for a range of point loads.
