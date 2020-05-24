# Deep Learning Nanodegree

## Project: Analyse Bike Sharing Patterns using Neural Networks

### By Vedavyas Kamath

### Goal/Aim
To design & build a neural network from scratch using numpy and train it to predict daily bike rental ridership. The goal of this project is to understand what happens behind the scenes of neural network before diving deeper into other tools like Pytorch/TensorFlow.

### Dataset:
The data was provided by Udacity for this project which is present in the `Bike-Sharing-Dataset` folder. This dataset has the number of riders for each hour of each day from January 1 2011 to December 31 2012 which we will be using to train our neural network.

### Project Overview
This project is broken down into 2 main files as below with specific tasks performed in each file:

**Notebook : Neural_Network_BikeSharing_Pattern.ipynb**
* Load in the data.
* Explore the data and prepare/pre-process the data for analysis.
* Run some unit tests to check for correctness of implementation.
* Finally call functions that train, test the model and visualise the results.

**Python Script : my_answers.py**
* Define the structure of the neural network from scratch by defining the number of layers, intial weights and parameters.
* Using Numpy, implement the different functions required : sigmoid activtaion, train function by making a feed-forward pass and then a function for back-propagation, updating the weights.
* Set hyper-paremeters so that the network is able to train well and give good results.


### Software Requirements
This project requires **Python 3.x** and the following Python libraries installed:
- [NumPy](http://www.numpy.org/)
- [Pandas](https://pandas.pydata.org/)
- [Matplotlib](https://matplotlib.org/)
- [Unittest](https://docs.python.org/2/library/unittest.html)



