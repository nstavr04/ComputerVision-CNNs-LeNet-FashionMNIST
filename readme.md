# Assignment 4: CNN Model Training and Evaluation

## Overall Goal
The goal of this assignment is to gain hands-on experience in training and validating CNN models and reporting their performance. This assignment serves as the foundation for the final assignment.

## Software and Installation
We will be programming in Python, preferably version 3.6 or above. Pytorch will be used for this assignment, which can be easily installed once Python is installed.

## Data
The dataset used for this assignment is the Fashion MNIST dataset, which is already available in Pytorch. It consists of 60,000 training images and 10,000 test images. Each image is a grayscale image of size 28x28 and belongs to one of ten possible class labels.

## Tasks
1. Import the Fashion MNIST dataset and split it into training, validation, and test sets.
2. Recreate the LeNet-5 architecture as the baseline model.
3. Create four model variants, each differing from the previous model by one aspect, aimed at improving performance.
4. Train and validate each model for up to 15 epochs, storing training and validation loss and accuracy.
5. Choose the best architecture based on the validation set and plot a training/validation loss graph for each model.
6. Test the best-performing model on the test set and compare it with a model trained on both training and validation sets.
7. Report the architecture, parameters, loss graphs, and model weights for all five models.
8. Discuss the results, comparing the four variants with the baseline model.
9. Analyze the differences between the best model's performance on the validation and test sets.
10. Implement choice tasks, such as decreasing the learning rate, k-fold cross-validation, output layers, data augmentation, t-SNE visualization, or dataset customization.