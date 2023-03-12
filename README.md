
# Deep Learning and Dropout-Based Post Training Confidence with TensorFlow

This repository contains code for the "Deep Learning EX2" exercise, which involves implementing and modifying a TensorFlow-based classifier for recognizing digits from the MNIST dataset.


# Requirements
To run this code, you will need to have the following installed:

Python 3.x 

TensorFlow 2.x

Numpy

Matplotlib



The DL_EX2.ipynb notebook contains the code for implementing and modifying a TensorFlow-based classifier for recognizing digits from the MNIST dataset. The notebook contains the following sections:


## Description


Data loading: Loading the MNIST dataset of handwritten digits.

Model creation: Defining the model architecture using Keras.

Model training: Compiling and training the model on the MNIST dataset.

Model evaluation: Evaluating the performance of the trained model on the test dataset.

Model modification: Modifying the model architecture and activation functions, and evaluating the effect on performance.

Image interpolation: Generating a set of images using the interpolation equation I(alpha) = alpha * I1 + (1-alpha) * I2 and running the digit classifier on these images.
Dropout-based confidence estimation: Implementing dropout-based post-training confidence estimation and evaluating its effectiveness.

Testing the fashion model on digits and vice versa: Testing the performance of the fashion model on the MNIST dataset of handwritten digits and vice versa.

Exploring confidences and probabilities: Plotting histograms of the accuracies of the test examples for correctly and incorrectly classified objects, and analyzing the confidences and probabilities of the classifiers when run on the wrong type of data.

##  Acknowledgments

The initial code for the digit classifier is based on the TensorFlow tutorial for image classification on fashion items, which can be found at https://www.tensorflow.org/tutorials/keras/classification.
