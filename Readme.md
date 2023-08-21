Backpropagation Custom Implementation:

This repository contains a Python implementation of a neural network optimization process using different optimizers: Vanilla, Momentum, and Adam. The neural network's forward propagation, backward propagation, gradient checking, and optimization process are included in the code.

Overview:
The provided code demonstrates the following functionalities:

Loading Data: The initial step involves loading the dataset using the pickle library. The dataset is then divided into input features (X) and target values (y).

Forward Propagation: The forward propagation process is implemented using the provided neural network architecture. Sigmoid, tanh, and other activation functions are used to compute the network's output and intermediate values.

Backward Propagation: The backward propagation process calculates the gradients of the loss function with respect to the weights. These gradients are used to update the weights during optimization.

Gradient Checking: The code includes a function for gradient checking, comparing computed gradients with approximated gradients to ensure correctness.

Optimizers: Three optimizers are implemented: Vanilla, Momentum, and Adam. These optimizers update the weights of the neural network in order to minimize the loss function.

Comparison Plot: A plot is generated to visualize the loss versus epochs for each optimizer. This helps in comparing the convergence speed and effectiveness of the different optimizers.

Usage:
Load the data using the provided data loading script.
Implement forward propagation and backward propagation using the defined functions.
Choose an optimizer (Vanilla, Momentum, or Adam) and set its hyperparameters.
Utilize the optimizer to train the neural network and monitor the loss convergence.
Compare the results using the comparison plot generated at the end.

Observations:
Vanilla and Adam optimizers gradually converge over increasing epochs.
The Momentum optimizer achieves quick optimization in a few epochs, but a loss deflection occurs.
The Vanilla optimizer attains the best loss of 0.0000045190 in 43 epochs.
Overall, the Adam optimizer demonstrates the best performance, converging quickly and consistently.
Feel free to experiment with different hyperparameters, network architectures, and optimizers to better understand their effects on training performance and convergence.