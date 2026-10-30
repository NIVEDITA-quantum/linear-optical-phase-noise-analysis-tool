# Linear-Optical Phase Noise Analysis Tool

## About the Project

This project focuses on studying the effect of phase noise on linear-optical quantum circuits using Python and the Perceval framework.

The project includes a simulation model that introduces random Gaussian phase noise into phase shifters and observes its effect on the output photon probability distributions.

It also includes a user testing feature that allows users to enter their own linear-optical circuit code and analyse how the circuit performs under different levels of phase noise.

The Bhattacharyya coefficient (BC) is used to compare the ideal and noisy output distributions. Different circuit configurations are tested to understand how circuit complexity affects their performance.

A 90% reference threshold is used to compare the noise tolerance of different circuits. This is a project-specific reference for performance comparison.

## Main Features

- Simulation of ideal linear-optical circuits.
- Gaussian phase noise modelling.
- Custom circuit testing using user-provided code.
- Comparison of ideal and noisy output distributions.
- Performance analysis using the Bhattacharyya coefficient.
- Graphs showing the effect of phase noise on different circuit configurations.
- Comparison of circuit noise tolerance.

## Software and Libraries Used

- Python
- Perceval Framework
- NumPy
- Matplotlib
- Jupyter Notebook

## How to Run

1. Download the `Quantum_Phasenoise.ipynb` notebook.
2. Open it using Jupyter Notebook.
3. Install the required Python libraries.
4. Run the notebook cells in order.
5. Use the custom circuit testing section to enter and analyse a linear-optical circuit.

## Project Scope

The project mainly focuses on modelling phase noise and analysing its effect on linear-optical circuit output distributions. Other hardware-related factors are outside the scope of this study.
