# MNIST-Numbers-Classification
This project demonstrates a simple yet effective deep learning approach for classifying handwritten digits using the MNIST dataset. The MNIST dataset contains 70,000 grayscale images of digits (0 through 9), each 28x28 pixels in size.

Overview
The goal of this project is to build a neural network using TensorFlow/Keras that can accurately identify handwritten digits. The model is built using the Sequential API and includes the following architecture:

Input Layer: Images are flattened from 28x28 into 784-dimensional vectors.

Hidden Layer 1: Dense layer with 128 units and ReLU activation.

Hidden Layer 2: Dense layer with 32 units and ReLU activation.

Output Layer: Dense layer with 10 units (one for each digit) and Softmax activation for multi-class classification.

Features
End-to-end digit recognition using a simple neural network.

Trained on the MNIST dataset with high accuracy.

Clean and minimal model architecture, great for beginners.

Ideal for learning basic concepts of deep learning and classification.

Dataset
The MNIST dataset is loaded directly from tensorflow.keras.datasets and includes:

60,000 training images

10,000 test images

