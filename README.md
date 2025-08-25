# Computational-Intel-2025-PartB

This project implements a Genetic Algorithm (GA) for feature selection in the task of predicting Alzheimer’s disease using an Artificial Neural Network (ANN).

The dataset consists of 34 input features representing patient characteristics. The goal of the algorithm is to automatically determine which features should be retained or discarded in order to:

- Reduce the dimensionality of the input space (mitigating the curse of dimensionality).

- Improve the training efficiency of the neural network.

- Maintain or improve the classification accuracy of the model.

The GA searches for the optimal subset of features by balancing model performance with feature reduction. The optimal ANN architecture identified in Part A of the study is used as the evaluation model.

Techniques referenced:

- Genetic Algorithms for feature subset selection

- Neural Networks for Alzheimer’s prediction

- Dimensionality reduction approaches such as PCA, Pearson correlation, and dropout (for comparison)
