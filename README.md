# ANN_Regression

This repository contains the implementation of a simple neural network using a synthetically generated dataset.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Requirements](#requirements)
- [Results](#results)
- [Acknowledgements](#acknowledgements)

## Introduction

This project demonstrates how to create a synthetic dataset, build and train a simple neural network model using TensorFlow, and visualize the results using Matplotlib. The dataset consists of 2D input features and a target value calculated with a combination of cosine functions. The goal is to fit the neural network model to the data and visualize its predictions.

## Dataset

- **Input Features (X):** 1000 samples with 2 features each, randomly generated and uniformly distributed between -3 and +3.
- **Target Value (Y):** Calculated using `Y = cos(2*X) + cos(3*X).

## Model Architecture

The neural network model has the following architecture:

- **Input Layer:** Takes input with shape (2,).
- **Hidden Layer:** Dense layer with 128 neurons and ReLU activation function.
- **Output Layer:** Dense layer with a single neuron to produce the output.

## Requirements

- Python 3.x
- NumPy
- Matplotlib
- TensorFlow


## Results
Training Loss: <br> The training loss decreases over epochs, indicating that the model is learning from the data. The final loss value is recorded from the training history plot.<br>
Prediction Surface:<br>
The first surface plot shows the model’s predictions over the range of the training data. It demonstrates how well the model fits the data in the training range.
The second surface plot with extrapolation displays the model’s predictions over a broader range. It provides insight into how the model performs beyond the training data. Note that extrapolation performance can vary and might not always be reliable.

## Acknowledgements
TensorFlow and Keras for building the neural network model.
Matplotlib for visualization.


