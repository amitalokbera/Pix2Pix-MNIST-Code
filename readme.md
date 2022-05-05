# Implementation of Pix2Pix on MNIST Dataset using PyTorch

This repo contains code to train Pix2Pix GAN model from scratch on custom MNIST dataset.

![mnist_image](https://i.imgur.com/VfS9p37.png)

## Installation

Make sure to install all the required libaries using requirements.txt file

```python
pip install -r requirements.txt
```
## Usage

To train the model

```python
python train.py
```

## Config

All the config details are stored in config.py

- LEARNING_RATE = set learning rate of the model
- BATCH_SIZE = set no. of training images utilized in one epoch
- NUM_WORKERS = set no. of CPU cores to use
- IMAGE_SIZE = set image resolution
- NUM_EPOCHS = no. of epochs to train model
