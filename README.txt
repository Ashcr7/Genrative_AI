GENERATIVE AI MODEL


This repository contains code for training and evaluating an image classification model using the Fashion MNIST dataset. The model is designed to classify grayscale images of fashion items into one of ten classes.

Dataset
The Fashion MNIST dataset is used for training and evaluating the model. It consists of 60,000 28x28 grayscale images in 10 different classes, with 6,000 images per class. The dataset is split into training, validation, and test sets.

Model Architecture
The model architecture consists of a convolutional layer, max-pooling layer, flattening layer, and two dense layers. The final layer uses softmax activation for multi-class classification.

Training
The model is trained for 5 epochs using the Adam optimizer and sparse categorical crossentropy loss. The training process includes validation on a separate validation set to monitor model performance.

Evaluation
The trained model is evaluated on the test set, and the accuracy is reported. Additionally, the training history, including accuracy and validation accuracy over epochs, is visualized using matplotlib.

Usage
Dependencies: Ensure that you have the required dependencies installed. You can install them using:



Model Saving: The trained model is saved as "image_classification_model.h5."

Files
image_classification_model.py: Python script for loading the Fashion MNIST dataset, building, training, and evaluating the image classification model.
image_classification_model.h5: Saved model file after training.


Author
Ayush Aggarwal

Acknowledgments
This code is based on the Fashion MNIST dataset and TensorFlow documentation.
Fashion MNIST dataset