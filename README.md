# Face generation with DCGANs

## Project overview

This project implements a deep convolutional generative adversarial networks (DCGANs) on a dataset of faces to aim to generate images of new and realistic human faces. 

### Data

For this project a subset of [CelebFaces Attributes Dataset (CelebA)](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) was used.

Download a subset of [CelebA dataset](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/November/5be7eb6f_processed-celeba-small/processed-celeba-small.zip). Unzip the folder and place it in the folder of the project. The location of the images for use the tool `ImageFolder` from Pytorch would be `face-project/processed_celeba_small/celeba. The folder contain a 24,396 images.



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
