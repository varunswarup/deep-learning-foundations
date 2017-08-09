# Image Classification for Computer Vision #

## Overview ##

In this project, I built a convolutional neural network (or ConvNet) to recognize and classify new images based on a pre-defined set of known, labeled images. The convnet was implemented using TensorFlow and was trained on the [CIFAR-10 dataset](https://www.kaggle.com/c/cifar-10), which consists of 60K images of ten different objects. I preprocessed the dataset using normalization and one-hot encoding. I implemented the convnet model with convolutional, max pool and fully-connected layers, and tuned the hyperparameters (including keep_probability) in conjunction with the filter size and strides params for the convolutional and max pooling layers.
