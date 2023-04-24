# CIFAR-10 Classification using CNN

### Description

This code performs image classification on the CIFAR-10 dataset using a Convolutional Neural Network (CNN) model. The model is built using TensorFlow and has two convolutional layers, one max pooling layer, one dropout layer, two dense layers with ReLU activation, and one output layer with softmax activation.

### Installation

To run this code, you need to have 
mlxtend
 and 
tensorflow
 libraries installed. You can install 
mlxtend
 using the following command:

```
!pip install mlxtend==0.21.0
```

And you can install 
tensorflow
 using the following command:

```
!pip install tensorflow
```

### Usage

The code loads the CIFAR-10 dataset, preprocesses the data by scaling the pixel values to a range of 0 to 1, builds the CNN model, and trains the model using the training set. The code also plots the training and validation accuracy values and the training and validation loss values for each epoch, and displays a confusion matrix for the predicted and actual labels of the test set.

To use this code, you can simply run the entire code block. However, if you want to modify the model architecture or the training parameters, you can make the necessary changes in the code.

### License

This code is licensed under the MIT License.