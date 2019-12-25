# FinTech-Time-Series
Quantum Machine Learning for FinTech and Time Series Data

## Quantum Neural Networks for FinTech Time Series Function Fitting
This repository is for developing quantum neural network models for fitting one-dimensional time series data and noisy signals. It is modified from the model presented in PennyLane [Function fitting with a quantum neural network](https://pennylane.ai/qml/app/quantum_neural_net.html). We modify the code presented in the default notebook downloaded from PennyLane so that it works using synthetic data created by the user. 

![image](noisy_cosine)

After training the quantum neural network learns to smooth the noisy cosine function as can be seen in the green plots:

![image](noisy_cosine_trained)

We also provide an example model trained on data from the ```.csv``` file on [Australian pharmaceutical company sales data](https://raw.githubusercontent.com/selva86/datasets/master/a10.csv). 

![image](drug_sales)
