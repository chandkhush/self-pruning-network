# Self-Pruning Neural Network

This project implements a self-pruning neural network using learnable gates and sparsity regularization.

# Objective

To build a neural network that can automatically remove less important weights during training.

# Method
Each weight has a learnable gate (0–1)
Final weight = weight × gate
Loss = Classification Loss + λ × Sparsity Loss

# Results 

<img width="161" height="47" alt="image" src="https://github.com/user-attachments/assets/0ba5272a-7b8f-49bb-a92f-9e5efd39c3a7" />

# Graph
<img width="783" height="524" alt="image" src="https://github.com/user-attachments/assets/6f8cc6fe-b688-4326-a4f8-594b7939b781" />



