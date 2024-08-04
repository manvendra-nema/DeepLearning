# 🧠 Deep Learning

## Implementing Perceptron Training Algorithm (PTA)

Implementation of a Perceptron Training Algorithm (PTA) in Python. The PTA updates weights when an error is made, following.

### 📋 Task Details

#### 📈 Calculation of Steps for Convergence

The number of steps necessary for convergence for the following operations has been calculated:

1. Two variables: AND
2. Two variables: OR
3. One variable: NOT

#### 🖼️ Drawing Decision Boundary

Decision boundaries at each step of learning have been drawn for all three operations (AND, OR, NOT).

Example:

![AND](https://github.com/manvendra-nema/Fundamental-of-DeepLearning/assets/53614640/814261ee-127c-48f7-8025-5dca78636921)
![OR](https://github.com/manvendra-nema/Fundamental-of-DeepLearning/assets/53614640/6c55c14c-5b47-4737-9f5b-743cdf5da806)
![NOT](https://github.com/manvendra-nema/Fundamental-of-DeepLearning/assets/53614640/dc80ac44-1736-40bc-9589-851771b9cf1c)
![Decision Boundary](https://github.com/manvendra-nema/Fundamental-of-DeepLearning/assets/53614640/25ce5b69-39d1-494e-8f8b-f12ee349746d)
![XOR](https://github.com/manvendra-nema/Fundamental-of-DeepLearning/assets/53614640/94275018-d9a7-4e1e-9333-210e3c4791c2)

#### ❌ Demonstration of XOR Operation

Theoretical demonstration and practical code implementation show that PTA cannot compute XOR operation. The output or decision boundary at each step validates this observation.

## 🚀 Implementation of Gradient Descent Algorithm

Implementation of the Gradient Descent Algorithm in Python from scratch to solve the optimization problem:

**_f(x₁, x₂) = x₁² + αx₂² - x₁*x₂ - x₁ - x₂_**

### 📋 Task Details

#### 📝 Gradient Descent Function

A function has been implemented to execute the Gradient Descent Algorithm. This involves differentiation and weight updation.

#### 📊 Convergence Report

Using initial values of x₁, x₂, and step size = 0.1 as initial conditions, the number of iterations required for convergence has been reported.

#### 📉 Plotting Iteration vs. Value of Function

A plot illustrating the iteration versus the value of the function f for the given setup has been generated. (x-axis = iteration no., y-axis = value of the function f in that iteration)

#### 📏 Iterations vs. Step Size

Five different values of step size in the interval [0, 2] have been chosen arbitrarily. The number of iterations required to converge for each step size has been determined and plotted (x-axis = step size, y-axis = iterations required to converge). The initial condition of x₁ and x₂ remains the same in all cases.

#### 🔍 Iterations vs. α (Alpha)

Five values of α (Alpha) in the interval [0, 1] have been chosen arbitrarily. The number of iterations required for each value of α has been determined and plotted (x-axis = α, y-axis = iterations required to converge). The initial condition of x₁ and x₂ remains the same in all cases.

#### 💡 Exploring γ = -1

The Gradient Descent implementation has been run for γ = -1, and a plot depicting Iteration versus the value of the function f in that iteration has been generated (x-axis = Iteration number, y-axis = value of the function f in that iteration). Observations and possible explanations for the observed behavior have been discussed.

## 🤖 Implementation of Multilayer Perceptron (MLP) from Scratch

Implement a Multilayer Perceptron (MLP) in Python from scratch, along with a modular Deep Learning Toolkit for training the MLP on the Fashion-MNIST dataset.

### 📋 Task Details

#### 🧠 Implementation of MLP

The MLP is constructed with the following network structure:

- Input: 784
- Output: 10
- Hidden layers: >= 1, with any number of neurons

Forward propagation and backward propagation have been implemented from scratch for the constructed neural network in the provided toolkit.py file.

#### 🛠️ Network Configurations

Appropriate sizes of hidden layers, learning rate, and other hyperparameters have been chosen.

#### 📊 Analysis of Model

Various combinations of activation functions and weight initialization techniques have been analyzed and reported.

a. **Activation Functions:**

- Activation functions for all hidden layers: Sigmoid or ReLU
- Output layer activation: Softmax

Implementation of activation functions and their differentials has been done.

b. **Weight Initialization:**

- Initial functions for all layers: All zeros or Normal/Gaussian

#### 📈 Results and Plots

For the combinations of activation and weight initialization techniques, the following plots have been generated and analyzed:

- **Loss plot:** Training Loss and Validation Loss vs. Epochs
- **Accuracy plot:** Training Accuracy and Validation Accuracy vs. Epochs

### 🛠️ How to Use

To run the code and observe the results:

- The results including loss and accuracy plots for various combinations of activation functions and weight initialization techniques are provided in the repository.
