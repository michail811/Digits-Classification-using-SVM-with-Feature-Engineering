Digits Classification using SVM with Feature Engineering

This project focuses on digit classification using Support Vector Machines (SVM) with various feature engineering techniques. The dataset used is the MNIST dataset, and the classification task involves distinguishing between digits greater than 4 and those less than or equal to 4.

Techniques and Features
Data Preprocessing:

Loading and splitting the MNIST dataset into training and test sets.
Reshaping the data to a flat format (28*28 to 784).
Sampling 1/5 of the training set to create a balanced dataset.
Binary Classification:

Converting the default multi-class problem into binary classification.
Assigning the label 1 to digits greater than 4 and 0 to digits less than or equal to 4.
SVM with Linear Kernel:

Attempting to use a linear kernel for SVM.
Performing grid search for parameter tuning.
SVM with Polynomial Kernel:

Employing a polynomial kernel for SVM.
Conducting a custom search for polynomial kernel parameters.
SVM with PCA (Principal Component Analysis):

Applying PCA for dimensionality reduction.
Evaluating the impact on SVM performance.
SVM with LDA (Linear Discriminant Analysis):

Utilizing LDA for feature extraction.
Assessing SVM performance after LDA.
SVM with LDA and PCA Combined:

Combining LDA and PCA for feature engineering.
Analyzing the impact on classification accuracy.
