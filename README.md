# Face generation with DCGANs

## Project overview

This project implements a deep convolutional generative confrontation network (DCGAN) on a face dataset with the aim of generating images of new and realistic human faces.

### Data

For this project a subset of [CelebFaces Attributes Dataset (CelebA)](http://mmlab.ie.cuhk.edu.hk/projects/CelebA.html) was used. The dataset can be download [here](https://s3.amazonaws.com/video.udacity-data.com/topher/2018/November/5be7eb6f_processed-celeba-small/processed-celeba-small.zip). Unzip the folder and place it in the folder of the project, at location `face-project/processed_celeba_small`. The folder contain a 24,396 images.

### Hyperparameters

The hyperparameters were chosen based on the original paper *Unsupervised Representation Learning with Deep Convolutional Generative Adversarial Networks*. `conv_dim` was set in 64 but it can be changed.

| Hyperparameters  | Value   | 
| ------------------| ------ |
| conv_dim (D, G)   | 64     | 
| batch_size        | 128    | 
| z_size            | 100    | 
| learning rate     | 0.0002   | 
| LeaklyRelu slope  | 0.2    | 

### Technologies used:

* Python, numpy
* Generative Adversarial Networks (GANs) 
* DCGANs
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
