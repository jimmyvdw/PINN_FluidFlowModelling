# Fluid Flow Velocity Field Prediction using Neural Networks and Physics-Informed Neural Networks

This Jupyter notebook demonstrates the use of TensorFlow, a Python package for deep learning, to predict fluid flow velocity fields. The notebook explores two approaches: neural networks and physics-informed neural networks (PINNs). The physics-informed approach incorporates Navier-Stokes (N-S) and continuity equations to improve the prediction of fluid flow.

## Table of Contents

- [Introduction](#introduction)
- [Prerequisites](#prerequisites)
- [Usage](#usage)
- [Approaches](#approaches)
- [File Structure](#file-structure)
- [Acknowledgements](#acknowledgements)

## Introduction

Fluid flow velocity field prediction is essential in various engineering applications, including aerospace, automotive, and environmental engineering. Traditional methods rely on solving partial differential equations (PDEs) based on physics principles. However, machine learning approaches, such as neural networks, offer an alternative for predicting complex fluid dynamics behaviors.

This notebook demonstrates the implementation of neural networks and physics-informed neural networks for fluid flow velocity field prediction using TensorFlow.

## Prerequisites

- Python 3.x
- Jupyter Notebook
- TensorFlow
- NumPy
- Matplotlib
- Pandas

You can install the required packages using the following pip commands:

```
pip install tensorflow numpy matplotlib pandas
```

## Usage

1. Ensure you have the required prerequisites installed.
2. Download the Jupyter notebook file (`PINN_tutorialScript.ipynb`).
3. Place your training data in a CSV file.
4. Update the notebook to read the training data from the CSV file.
5. Open the Jupyter Notebook and run the cells in the notebook to understand and experiment with the fluid flow velocity field prediction using neural networks and physics-informed neural networks.

## Approaches

### Neural Networks Approach

- In this approach, we use a standard neural network to directly predict the fluid flow velocity field without considering the underlying physics.

![Physics-Informed Neural Networks](/NNTutorial/NNPlots.png)


### Physics-Informed Neural Networks (PINNs) Approach

- PINNs incorporate physics principles, such as the Navier-Stokes (N-S) and continuity equations, into the neural network architecture.
- The N-S equation models the balance of forces and predicts fluid flow behavior.
- The continuity equation ensures mass conservation and aids in accurate velocity field prediction.

- The continuity equation ensures mass conservation and aids in accurate velocity field prediction.

![Physics-Informed Neural Networks](/PINNTutorial/PINNPlots.png)

## File Structure

```
/
|-- fluid_flow_prediction.ipynb   # Jupyter Notebook file
|-- ...
```
