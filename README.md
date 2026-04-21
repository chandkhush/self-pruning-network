#Self-Pruning Neural Network

This project implements a self-pruning neural network using learnable gates and sparsity regularization.

**Objective**

To build a neural network that can automatically remove less important weights during training.

**Method**
Each weight has a learnable gate (0–1)
Final weight = weight × gate
Loss = Classification Loss + λ × Sparsity Loss

**Results**
Lambda	    Accuracy	  Sparsity
0.1	        18.67%     	43.17%
0.5	        18.97%	    44.88%
1.0       	21.78%	    45.31%



