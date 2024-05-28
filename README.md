# Medical-Imaging-Differential-Privacy
Implementing Differential Privacy into medical imaging ML prediction.

# Iris Dataset Analysis

This repository contains code for analyzing the Iris dataset using various machine learning algorithms and differential privacy techniques.

## Dataset Description

The Iris dataset is a classic dataset in the field of machine learning and statistics. It contains 150 samples of iris flowers, each with four features (sepal length, sepal width, petal length, and petal width). The goal is to classify the iris flowers into one of three species: Setosa, Versicolor, or Virginica.

## Code Overview

The analysis includes the following steps:

1. Loading and exploring the dataset.
2. Splitting the dataset into training and test sets.
3. Exploring the correlation among the features.
4. Implementing the k-Nearest Neighbors (kNN) algorithm.
5. Visualizing the learning curve for the chosen classifier.
6. Predicting labels for new datasets and test data.
7. Implementing the Decision Tree algorithm.
8. Saving and loading the trained model.
9. Implementing differential privacy techniques using Laplace mechanism.
10. Evaluating the performance of kNN and Decision Tree with differential privacy.

## Getting Started

To run the code:

1. Clone this repository.
2. Install the required dependencies (`scikit-learn`, `pandas`, `matplotlib`, `seaborn`, `joblib`, `diffprivlib`).
3. Execute the code in a Python environment.

## Requirements

- Python 3.x
- scikit-learn
- pandas
- matplotlib
- seaborn
- joblib
- diffprivlib

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
