# CNN-MNIST Classification with TensorFlow and Keras
## Objective
The primary goal of this project is to develop a Convolutional Neural Network (CNN) using TensorFlow and Keras for classifying handwritten digits from the MNIST dataset. The objective is to achieve high accuracy by optimizing the CNN model.

## Description
This project utilizes the MNIST dataset, which contains 70,000 images of handwritten digits (0-9). The dataset is split into a training set (60,000 images) and a test set (10,000 images). A CNN model was built using TensorFlow and Keras to classify these images.

## Data Preprocessing:
Reshape images into the required input format and normalize pixel values.
One-hot encode the target labels.
## CNN Architecture:
Layers include Conv2D, MaxPooling2D, Flatten, Dense, and Dropout to enhance performance and avoid overfitting.
## Training & Validation:
The model is trained using the training data with a validation split. Early stopping is used to prevent overfitting.
## Evaluation:
The model is evaluated on the test set, yielding high accuracy (~99%).
## Conclusion
The CNN model successfully classified the MNIST digits with a test accuracy of over 99%. This demonstrates the power of Convolutional Neural Networks in image classification tasks. The project achieved the desired objective, and the model can be further optimized with advanced techniques or extended to more complex datasets.
