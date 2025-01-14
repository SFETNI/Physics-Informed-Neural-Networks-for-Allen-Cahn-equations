# Physics-Informed Neural Networks for Allen-Cahn Equations

This repository provides a simple and efficient implementation of **Physics-Informed Neural Networks (PINNs)** to solve the **Allen-Cahn equations**. PINNs leverage neural networks to directly solve partial differential equations (PDEs) by incorporating physical laws into the loss function. 

## Applications

Although the primary focus is on solving the Allen-Cahn equations, the techniques demonstrated here can also be applied to other similar equations, such as:

- **Cahn-Hilliard equations**: Used to model phase separation in binary mixtures and other phenomena involving free boundaries.
- **Navier-Stokes equations**: Governs fluid dynamics, modeling the behavior of incompressible flows.

## Repository Structure

- **`AC.mat`**: Data file containing information for the Allen-Cahn equations.
- **`PINN_AC.ipynb`**: Jupyter Notebook with the full implementation of the PINN model, training, and solution visualization.
- **`save_figs`**: Directory containing saved figures from the experiments.

## Requirements

To run this repository, ensure that the following libraries are installed:

- TensorFlow
- NumPy
- Matplotlib
- SciPy

You can install the necessary libraries using `pip`:

```bash
pip install tensorflow numpy matplotlib scipy

