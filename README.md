# FinTech-Time-Series
Quantum Machine Learning for FinTech and Time Series Data

## Quantum Neural Networks for FinTech Time Series Function Fitting
This repository is for developing quantum neural network models for fitting one-dimensional time series data and noisy signals. It is modified from the model presented in PennyLane [Function fitting with a quantum neural network](https://pennylane.ai/qml/app/quantum_neural_net.html). We modify the code presented in the default notebook downloaded from PennyLane so that it works using synthetic data created by the user. 

![alt text](noisy_sine.png)

## Training Data
In this very basic setup, there were only 4-layers in the quantum neural network, initialized with random weights. The model went through 50 iterations and had the following training data:

```

```

## Prediction Plots
After training the quantum neural network learns to smooth the noisy sine function as can be seen in the red plots:

![alt text](noisy_sine_trained.png)


