# ANN_Regression

This Repository contains implementation of simple neural network using a synthetically generated dataset.


## Table of Contents
- [Introduction](#Introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Requirements].(#Requirements).
- [Results](#Results)
- [Acknowledgements](#Acknowledgements)

## Introduction

This project demonstrates how to create a synthetic dataset, build and train a simple neural network model using TensorFlow, and visualize the results using Matplotlib. The dataset consists of 2D input features and a target value calculated with a combination of cosine functions. The goal is to fit the neural network model to the data and visualize its predictions.

## Dataset
Input Features (X): 1000 samples with 2 features each, randomly generated and uniformly distributed between -3 and +3.<br>
Target Value (Y): Calculated using Y = cos(2*X[:,0]) + cos(3*X[:,1]), where X[:,0] and X[:,1] are the first and second features of the input, respectively.<br>

## Model Architecture

The neural network model has the following architecture:<br>

Input Layer: Takes input with shape (2,).<br>
Hidden Layer: Dense layer with 128 neurons and ReLU activation function.<br>
Output Layer: Dense layer with a single neuron to produce the output.<br>

## Requirements
Python 3.x
NumPy
Matplotlib
TensorFlow

## Results
Training Loss: The training loss decreases over epochs, indicating that the model is learning from the data. The final loss value is recorded from the training history plot.<br>
Prediction Surface:<br>
The first surface plot shows the model’s predictions over the range of the training data. It demonstrates how well the model fits the data in the training range.
The second surface plot with extrapolation displays the model’s predictions over a broader range. It provides insight into how the model performs beyond the training data. Note that extrapolation performance can vary and might not always be reliable.

## Acknowledgements
TensorFlow and Keras for building the neural network model.
Matplotlib for visualization.


