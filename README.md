# Multi Layer Perspetron Neural Network

This code performs an in-depth analysis of training a neural network using PyTorch, specifically focusing on the impact of different hyperparameters such as learning rates and batch sizes.

## Part 1: Initial Model Training and Evaluation

### Data Preparation
The code begins by downloading the MNIST dataset using torchvision and splitting it into training and validation sets.

### Model Architecture
A simple neural network (`SimpleNN`) with multiple fully connected layers is defined.

### Model Training Loop
The script then proceeds to train the model using a specified number of epochs. Training and validation losses, as well as accuracies, are recorded for each epoch.

### Visualization
Two subplots are generated to visualize the training progress:
1. **Loss Plot:** Displays the training and validation losses over epochs.
2. **Accuracy Plot:** Displays the training and validation accuracies over epochs.

## Part 2: Hyperparameter Tuning - Learning Rates

### Learning Rate Variation
The code then explores the impact of different learning rates on model training. It iterates through a range of learning rates, reinitializes the model, and trains it for a fixed number of epochs.

### Learning Rate Visualization
Two subplots are generated to visualize the effect of learning rates:
1. **Loss Plot:** Displays the training and validation losses for each learning rate.
2. **Accuracy Plot:** Displays the training and validation accuracies for each learning rate.

## Part 3: Hyperparameter Tuning - Batch Sizes

### Batch Size Variation
Similar to learning rates, the code explores the impact of different batch sizes on model training. It iterates through a range of batch sizes, reinitializes the model, and trains it for a fixed number of epochs.

### Batch Size Visualization
Two subplots are generated to visualize the effect of batch sizes:
1. **Loss Plot:** Displays the training and validation losses for each batch size.
2. **Accuracy Plot:** Displays the training and validation accuracies for each batch size.

## Observations
- The initial model training provides insights into the baseline performance.
- Learning rate variations showcase the impact of this hyperparameter on convergence and model accuracy.
- Batch size variations demonstrate how different batch sizes affect the model's ability to generalize and converge.


