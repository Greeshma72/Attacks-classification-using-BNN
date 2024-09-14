# Attacks-classification-using-BNN
Attack Classification using Bayesian Neural Network

Overview:

This project implements a Bayesian Neural Network (BNN) for classifying network attacks using TensorFlow and TensorFlow Probability. A BNN introduces uncertainty in the neural network model by incorporating probabilistic reasoning, which is particularly useful in cases where overconfidence in predictions could lead to incorrect outcomes, such as in security or anomaly detection scenarios.

Features:

Bayesian Neural Networks: Implementation of a probabilistic neural network for attack classification.
TensorFlow & TensorFlow Probability: Utilizes TensorFlow's robust machine learning framework and TensorFlow Probability for BNN layers.
Graph Visualization: Employs NetworkX and Graphviz to create visual representations of the model's architecture.
Data Preprocessing: Includes scaling and encoding steps for the dataset.
Dataset: Loads and processes network security data for attack classification tasks.

Installation:
Ensure that you have the following dependencies installed:

!apt-get install -y graphviz libgraphviz-dev
!pip install pygraphviz pandas numpy matplotlib tensorflow tensorflow_probability scikit-learn networkx

Project Structure
Pre-requisites:

TensorFlow and TensorFlow Probability are required to construct the Bayesian Neural Network.
NetworkX and Graphviz are used for visualizing the structure of the neural network.

Data Preprocessing:

Data is preprocessed using pandas for handling data frames.
Features are scaled using StandardScaler.
Categorical features are encoded using OneHotEncoder.
Data is split into training and test sets using train_test_split.\

Model Training:

A Bayesian Neural Network model is constructed using TensorFlow's probabilistic layers.
The model is trained on the dataset to classify different types of network attacks.

Visualization:

The architecture of the model is visualized using NetworkX and Graphviz.
Usage
To use this project, follow the steps:

Clone this repository.
Ensure all dependencies are installed.
Run the provided Jupyter notebook to preprocess data, train the BNN, and visualize results.

Results:
The model outputs classification results for various network attacks.
It includes uncertainty quantification, which provides additional insights into model predictions.
