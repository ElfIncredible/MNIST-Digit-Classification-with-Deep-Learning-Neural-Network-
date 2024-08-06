
# MNIST Digit Classification with Deep Learning (Neural Network)


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


## Dataset


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
