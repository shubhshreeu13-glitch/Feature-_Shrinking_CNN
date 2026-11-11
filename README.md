# Feature-Shrinking CNN

## Project Description
This project implements a Feature-Shrinking Convolutional Neural Network (CNN) using TensorFlow and Keras.

The model processes grayscale images of size 28×28 pixels and classifies handwritten digits from 0 to 9.

## Dataset
MNIST Handwritten Digit Dataset.

## Model Architecture
1. Input Layer: (28, 28, 1)
2. Conv2D: 16 filters, 3×3 kernel, strides (2,2), padding same, ReLU
3. Conv2D: 32 filters, 3×3 kernel, strides (1,1), padding valid, ReLU
4. Flatten Layer
5. Dense Layer: 10 neurons, Softmax activation

## Model Training
- Optimizer: Adam
- Loss Function: Sparse Categorical Crossentropy
- Epochs: 5
- Batch Size: 64

## Results
- Training Accuracy: 98.98%
- Validation Accuracy: 98.63%
- Test Accuracy: 98.67%
- Trainable Parameters: 50,890

## Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Google Colab

## Conclusion
The Feature-Shrinking CNN was successfully trained and achieved 98.67% test accuracy on the MNIST dataset.
