# Basic-tasks

Naive Bayes Classification on Iris Dataset


Overview

This repository contains a Jupyter Notebook showcasing the implementation of a Naive Bayes classifier on the famous Iris dataset. The steps include data exploration, model training, making predictions, and evaluating the model's performance.

Table of Contents:

Installation
Usage
Data Exploration
Data Splitting
Model Training
Making Predictions
Model Evaluation
Contributing
License
Installation
Clone the repository to your local machine:

bash

Copy code
git clone https://github.com/JoelFred20/Basic-tasks
cd Basic-tasks
Install the required dependencies:

bash

Copy code
pip install -r requirements.txt
Usage
Open the Jupyter Notebook NaiveBayes_Iris_Classification.ipynb to run the code interactively. Ensure you have Jupyter Notebook installed:

bash
Copy code
pip install jupyter
jupyter notebook
Data Exploration
Explore the basic information, summary statistics, and check for missing values in the Iris dataset. Visualizations include a count plot of the target variable and pair plots for feature distribution.

Data Splitting
Split the dataset into features (X) and the target variable (y). Further split it into training and testing sets using the train_test_split function from scikit-learn.

Model Training
Initialize and train a Gaussian Naive Bayes model using the training data.

Making Predictions
Use the trained model to make predictions on the test set.

Model Evaluation
Print a classification report containing precision, recall, and F1-score. Visualize the confusion matrix to understand the model's performance.

Contributing
Feel free to contribute by opening issues or creating pull requests. Your contributions are highly welcomed!
