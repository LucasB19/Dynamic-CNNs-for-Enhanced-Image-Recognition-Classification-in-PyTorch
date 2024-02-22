# CIFAR-10 Image Classification with PyTorch

This repository contains the implementation of a comprehensive deep learning pipeline for classifying images from the CIFAR-10 dataset, developed by Lucas Berry (Student ID: 220296948) for the module ECS6P9U/P/7026P. Utilizing PyTorch, this project demonstrates a complete workflow from data handling to model evaluation, focusing on the CIFAR-10 dataset that includes 60,000 32x32 color images across 10 different classes.

## Project Structure

### Part 1: Data Preparation
* Download and split the CIFAR-10 dataset.
* Create DataLoaders with a batch size of 64.
* Apply data augmentation techniques to enhance the model's generalization capability.
### Part 2: Model Architecture
* Design a neural network with a custom backbone and classifier.
* Implement a series of convolutional layers, adaptive pooling, and linear layers for effective feature extraction and classification.
### Part 3: Training Mechanics
* Employ cross-entropy loss and the Adam optimizer.
* Use the ReduceLROnPlateau scheduler for optimizing the learning rate.
### Part 4: Evaluation Strategy
* Integrate early stopping to prevent overfitting.
* Conduct hyperparameter tuning to find the optimal model configuration.
### Part 5: Testing and Results
* Analyze the impact of various hyperparameters on the model's accuracy.
* Achieve a testing accuracy of 88.48% through meticulous adjustments and optimizations.

## Installation

```bash
# Clone this repository
git clone https://github.com/LucasB19/image_recognition.git
```

```bash
# Navigate to the project directory
cd <project-directory>
```

```bash
# Install required libraries
pip install -r requirements.txt
```

## Usage
Ensure you have PyTorch and other required libraries installed. Modify the script according to your computational resources and preferences.

## Results

The project achieved a test accuracy of 88.48%, with detailed experimentation on different hyperparameters. For in-depth analysis, refer to the figures and tables included in the results folder.

## License

MIT

## Acknowledgements

* This project was developed as part of the coursework for ECS6P9U/P/7026P.
* CIFAR-10 dataset provided by the Canadian Institute for Advanced Research (CIFAR).
