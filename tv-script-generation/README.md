# TV Script Generation for The Simpsons #

## Overview ##

This project’s objective was to design and use a recurrent neural network (RNN) to generate TV script dialogues for a scene at Moe’s Tavern as featured in The Simpsons. The RNN was trained using part of the [Simpsons dataset of scripts from 27 seasons](https://www.kaggle.com/wcukierski/the-simpsons-by-the-data). As part of the data preprocessing, I created functions for word embedding conversions and tokenizing punctuation in the existing dataset. I made use of the tf.contrib.rnn module to build the RNN cell with dropout and one or more LSTM layers. I tuned various hyperparameters - such as the number of epochs, batch size, RNN size, and sequence length - while training the RNN.

## Prerequisites & Notes ##

1. In order to successfully run the Jupyter notebook, your Conda environment needs to have Numpy and Tensorflow installed, with TensorFlow version 1.0 or newer.
2. The RNN needs to be trained on a GPU-based instance or system.
