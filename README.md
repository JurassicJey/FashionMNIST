# Fashion MNIST Classification (93% accuracy)

This notebook demonstrates building, training, and evaluating a Convolutional Neural Network (CNN) to classify images from the Fashion MNIST dataset—a collection of 28x28 grayscale images across 10 clothing categories (e.g., T-shirts, trousers, shoes).

## Architecture

The model utilizes a CNN architecture with:
- **Convolutional Layers** to extract features from the images
- **Pooling Layers** to reduce spatial dimensions and complexity
- **Fully Connected Layers** for final classification
- **Output Layer** with softmax activation to output probabilities for each class

## Usage

1. **Data Preparation**: The notebook loads the Fashion MNIST dataset and splits it into training and testing sets.
2. **Model Training**: Defines, compiles, and trains the CNN model on the training data.
3. **Evaluation**: Evaluates model performance on the test set, reporting accuracy and loss.

## Requirements

To run this notebook, ensure you have:
- Python 3.x
- TensorFlow or PyTorch (based on your setup)
- Common libraries like NumPy and Matplotlib

## Customization

This notebook allows for customization:
- Adjust the CNN architecture (e.g., layers, filters, kernel sizes).
- Modify hyperparameters, such as learning rate, batch size, and epochs.
- Experiment with data augmentation techniques to enhance generalization.

---
