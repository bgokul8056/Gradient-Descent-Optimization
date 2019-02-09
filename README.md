# Gradient-Descent-Optimization

The aim of this project is to experiment with several gradient descent algorithms and hyperparameters in a neural network and study their effect on the rate of gradient descent, such as stability, speed and accuracy.

A 3 layer fully connected neural network is implemented using Python to classify the fashion MNIST dataset. 

The algorithms studied in this project are `No Momentum` , `Polyak's Classical Momentum` , `Nesterov's Gradient Descent` , `RmsProp` , `Adam`.

The hyperparameters varied are `learning rate`, `batch size` and the `number of iterations`.

The findings of this project are documented in the report 

## DATA Folder
This folder contains the Fashion MNIST training data.

## TASKS Folder
This folder contains the Python programs for each algorithm:
1. `Adam.py` contains implementation of the `Adam` algorithm.

2. `load_mnist.py` is used to load the `Fashion MNIST` dataset.
   
3. `GD.py` contains implementation of a neural network without any momentum.

4. `GDmomentum.py` contains implementation of the `Polyak's Classical Momentum` algorithm.

5. `RmsProp.py` contains implementaion of the `RmsProp` algorithm


## OUTPUTS Folder

This folder contains the results obtained from each algorithm.


## KERAS IMPLEMENTATION Folder
This folder contains the ipython notebook which contains the Keras implementation of this project and their results.


