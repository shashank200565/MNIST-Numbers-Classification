# MNIST-Numbers-Classification
Overview
This project implements a neural network for classifying handwritten digits from the MNIST dataset. The model achieves 97.82% accuracy on the test set.

Dataset

The MNIST dataset is automatically downloaded when running the script. It contains:

   -60,000 training images

   -10,000 test images

   -28x28 grayscale images of handwritten digits (0-9)
    
Model Architecture
The neural network consists of the following layers:

   -Input Layer: Flattens 28x28 images into 784-dimensional vectors

   -Hidden Layer 1: Dense layer with 128 units and ReLU activation

   -Hidden Layer 2: Dense layer with 32 units and ReLU activation

   -Output Layer: Dense layer with 10 units (one for each digit 0-9) with Softmax activation

Training Details

   -Epochs: 100

   -Optimizer: Adam

   -Loss Function: Categorical Crossentropy

   -Batch Size: 32 (default)

   -Validation Split: 20% of training data

Performance

The model achieves:

   -Training Accuracy: 99.4%

   -Test Accuracy: 97.82%
