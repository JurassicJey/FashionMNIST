
Fashion MNIST Classification - README
This notebook builds, trains, and evaluates a Convolutional Neural Network (CNN) to classify images
from the Fashion MNIST dataset, a collection of 28x28 grayscale images across 10 clothing categories
(e.g., T-shirts, trousers, shoes).

--- Architecture: ---
The model uses a CNN architecture, with:
  Convolutional Layers to extract image features
  Pooling Layers to reduce spatial dimensions
  Fully Connected Layers for classification
  Output Layer with softmax activation for class probabilities
  
--- Usage ---
Data Preparation: 
  The notebook loads the Fashion MNIST dataset, splitting it into training and testing sets.
Model Training: 
  Defines, compiles, and trains the model on the dataset.
Evaluation: 
  Assesses model accuracy and loss on the test set.
