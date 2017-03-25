# Bike Sharing

## Introduction

Using a dataset for a small bike renting company, this program creates a neural network and trains it, allowing for future predictions of how many users will rent a bike on any given day. In order to implement this, we preprocess the data through pandas and run it through a three layer neural network created with numpy. This was done for Udacity's Deep Learning Nanodegree Foundations program.

## Implementation

The neural network is three layers, meaning there is an input layer, a hidden layer, and an output layer. Each of the nodes in these layers are connected by weights, which are initialized to a normalized random value at the beginning. When training, we use partial derivatives to see the rate of change in the error with respect to the rate of change of each of the weights. Then, using gradient descent, we can update the weights. This process is run several times depending on the epoch parameter. 

Activation function: Sigmoid
Error function: Mean Squared Error

## Usage

When running the code, I recommend using an Anaconda virtual environment. You can download Anaconda 3 [here](https://www.continuum.io/downloads). Follow the instructions on the site to download Anaconda. 

Once you have Anaconda installed, go into cmd/terminal and type the following: 

```
> conda create -n "bike-sharing" python=3
```
This will create a conda virtual environment named bike-sharing. You can remove it with the conda-remove command if you wish in the future. Then, we need to activate the virtual environment. For Windows, type:
```
> activate bike-sharing
```
For linux/mac, type:
```
> source activate bike-sharing
```
Then, install the dependencies with:
```
> conda install numpy, pandas, jupyter notebook
```
Then, start up a jupyter notebook server to access the .ipynb file. You can look through the network and change parameters or add more features if you wish. Have fun!

## Dependencies

numpy, pandas, jupyter notebook
