# TV Script with RNN

## Project overview

This project implements a recurrent neural network (LSTM) for training a language model. This model is used to generate a new text, based on the patterns it learned from the training data.

The dataset was composed of scripts from the Seinfeld TV show.

### Hyperparameters

A import task in the project is to set the hyperparameters. The two most important parameters that control the model are `hidden_dim` and  `n_layers`. The `n_layers` usually takes a values from 2 or 3. In this project it was set as 2. For `hidden_dim` values as 128, 256 or 512 are usual.

The final hyperparameters were:

| Hyperparameters  | Value | 
| -------------- | --------- |
| sequence_length  | 30      | 
| batch_size       | 128     | 
| embedding_dim    | 200     | 
| hidden_dim       | 512     | 
| n_layers         | 2       | 

In order to improve the model the parameters can be changed.

### Technologies used:

* Python, numpy
* Neural networks 
* RNN, LSTM
* jupyter notebook, anaconda

## Installation

The project involves:

* Text processing: normalize and cleaning text
* Train the model: LSTM neural network
* Generate new script

Using [Anaconda](https://www.anaconda.com/products/individual), in an enviroment with python 3, install the following packages:
```
conda install jupyter, numpy, 
conda install -c pytorch pytorch
```
