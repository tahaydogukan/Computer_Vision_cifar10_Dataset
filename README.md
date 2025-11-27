# **CIFAR10 IMAGE CLASSIFICATION**

This project performs image classification on the CIFAR-10 dataset using a simple Multi-Layer Perceptron (MLP) model. The model flattens the images and passes them through fully connected layers to produce probability outputs for 10 different classes.

# **TECHNOLOGIES USED**

Python
TensorFlow / Keras
NumPy
Matplotlib
CIFAR-10 dataset

# **STEPS**

CIFAR-10 data is loaded and normalized.

Labels are converted to one-hot encoded format.

A simple MLP model consisting of Flatten + Dense layers is built.

The model is trained with a training–validation split.

Accuracy and loss graphs are plotted after training.

Model performance is evaluated on the test set (approximately 50% accuracy).

A sample image from the test set is predicted and compared with its true label.

# **CONCLUSION**

Using a basic MLP model, approximately 50% accuracy is achieved on the CIFAR-10 dataset, which is considered challenging for non-convolutional models. For better performance, CNN-based architectures are recommended.
