# Logistic-Regression-Practical-Implementation


This repository contains a practical implementation of Logistic Regression using the Iris dataset. The goal is to classify the species of iris flowers based on their sepal and petal measurements.

# Dataset:
The dataset used in this project is the Iris dataset, which includes the following features:

sepal_length: Length of the sepal

sepal_width: Width of the sepal

petal_length: Length of the petal

petal_width: Width of the petal

species: Species of the iris flower (setosa, versicolor, virginica)

# Steps:
Data Loading: Load the Iris dataset using seaborn.

Data Preprocessing: Filter out the 'setosa' species and map the remaining species to binary values (0 for versicolor, 1 for virginica).

Train-Test Split: Split the data into training and testing sets using train_test_split.

Model Training: Train a Logistic Regression model using the training data.

Hyperparameter Tuning: Use GridSearchCV to find the best hyperparameters for the Logistic Regression model.

Model Evaluation: Evaluate the model using accuracy and other relevant metrics.

Visualization: Use Seaborn to create visualizations of the data and model predictions.

# Requirements
Python 3.x

pandas

numpy

seaborn

scikit-learn

Usage
Clone the repository:

# bash
git clone https://github.com/yourusername/logistic-regression-practical-implementation.git
Navigate to the project directory:

# bash
cd logistic-regression-practical-implementation
Install the required packages:

# bash
pip install -r requirements.txt
Run the Jupyter Notebook to see the implementation:

# bash
jupyter notebook Logistic_Regression_Practical_Implementation.ipynb
Results
The model achieves a high accuracy in classifying the species of iris flowers. The hyperparameter tuning using GridSearchCV helps in finding the best parameters for the model, improving its performance.

# Contributing
Feel free to fork this repository, make improvements, and submit pull requests. Contributions are welcome!
