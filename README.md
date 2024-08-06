
# MNIST Digit Classification with Deep Learning (Neural Network)
Build a neural network with TensorFlow and Keras to recognize handwritten digits from the MNIST dataset. Train, evaluate, and use it to make predictions, which you then visualize.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Neural Network](#neural-network)
    - [Import Dependencies](#import-dependencies)
    - [Load the MNIST data from keras datasets](#load-the-mnist-data-from-keras-datasets)
    - [Image Labels](#image-labels)
    - [Building the Neural Network](#building-the-neural-network)
    - [Accuracy on test data](#accuracy-on-test-data)
    - [Confusion Matrix](#confusion-matrix)
    - [Building a predictive system](#building-a-predictive-system)

## Project Overview
This project aims to develop a system that can recognize handwritten digits using a neural network trained on the MNIST dataset. The system takes an input image of a handwritten digit, processes it to be compatible with the trained neural network, and predicts the digit. The entire pipeline includes data preprocessing, model training, evaluation, and real-time prediction on new images.

## Dataset
The [MNIST dataset](https://keras.io/api/datasets/mnist/) is a benchmark dataset in the field of machine learning and computer vision, widely used for training and testing image processing systems. It consists of 70,000 grayscale images of handwritten digits from 0 to 9, with each image being 28x28 pixels in size. The dataset is divided into two parts: 60,000 images for training and 10,000 images for testing. Each image is labeled with the corresponding digit it represents, making it an excellent resource for classification tasks. The simplicity and size of the MNIST dataset make it ideal for demonstrating the capabilities of neural networks and other machine learning algorithms in recognizing handwritten digits.

## Neural Network
### Import Dependencies
- Set up the environment for a machine learning project, specifically for working with image data.
- Ensure reproducibility by setting a random seed.

### Load the MNIST data from keras datasets
- Load the MNIST dataset.
- Inspect the structure and dimensions of the data.
- Print the pixel values and dimensions of a specific image.
- Display an image.
- Print its corresponding label.

### Image Labels
- Check the shapes and unique values of the label arrays.
- Normalize the image pixel values.
- Print the normalized pixel values of a specific image.

### Building the Neural Network
- Define a neural network architecture.
- Compile it with an optimizer and loss function.
- Train it on the MNIST dataset for 10 epochs.

### Accuracy on test data
- Evaluate the model on test data.
- Inspect and displays specific images and their predictions.
- Convert the model's probability outputs into class labels.

### Confusion Matrix
- Compute the confusion matrix to evaluate the classification performance of the neural network on the test dataset.
- Print it.
- Visualize it using a heatmap for better interpretability.

### Building a predictive system
- Process an input image of a handwritten digit.
- Make it compatible with the trained neural network.
- Predict and print the recognized digit.
