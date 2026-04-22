# Self-Pruning Neural Network

This project implements a self-pruning neural network using learnable gates and sparsity regularization.

# Objective

To build a neural network that can automatically remove less important weights during training.

# Method
Each weight has a learnable gate (0–1)
Final weight = weight × gate
Loss = Classification Loss + λ × Sparsity Loss

## Results Screenshot

![Results](./Screenshot%202026-04-22%20034240.png)

