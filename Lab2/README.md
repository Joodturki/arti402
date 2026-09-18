# Neural Networks from Scratch

This lab implements the main components of a neural network using Python and NumPy.

## Tasks

### Exercise 1: Equivalent Weight Matrix

- Combined two linear layers into one equivalent weight matrix.
- Compared the one-layer and two-layer outputs.

### Exercise 2: Activation Functions

- Implemented the ReLU activation function.
- Implemented the sigmoid activation function.

### Exercise 3: Dense Layer

- Created a dense layer with randomly initialized weights and zero biases.
- Implemented the forward pass for a batch of inputs.

### Exercise 4: Softmax

- Implemented the softmax activation function.
- Added numerical stability by subtracting the maximum value in each row.

### Exercise 5: Categorical Cross-Entropy

- Implemented categorical cross-entropy loss.
- Used clipping to prevent `log(0)`.

### Exercise 6: Numerical Derivative

- Approximated derivatives using the central difference method.

### Exercise 7: Gradient Descent

- Used numerical derivatives and gradient descent to minimize a function.

### Exercise 8: Backpropagation

- Calculated gradients through a neuron and ReLU activation.
- Verified the gradients using numerical derivatives.

### Assessment: Neural Network Training

- Built a neural network with two dense layers, ReLU, and softmax.
- Calculated the initial loss and accuracy.
- Trained the network using numerical gradients and gradient descent.
- Evaluated the final loss and classification accuracy.

## Libraries Used

- NumPy
- Matplotlib
- NNFS
