# Content: Model Evaluation and Validation
## Project: Predicting Boston Housing Prices

## Project Overview
In this project, we will apply basic machine learning concepts on data collected for housing prices in the Boston, Massachusetts area to predict the selling price of a new home. We will first explore the data to obtain important features and descriptive statistics about the dataset. Next, we will properly split the data into testing and training subsets, and determine a suitable performance metric for this problem. We will then analyze performance graphs for a learning algorithm with varying parameters and training set sizes. This will enable us to pick the optimal model that best generalizes for unseen data. Finally, we will test this optimal model on a new sample and compare the predicted selling price to the calculated statistics.

## Project Highlights
This project is designed to get acquainted to working with datasets in Python and applying basic machine learning techniques using NumPy and Scikit-Learn. Before being expected to use many of the available algorithms in the sklearn library, it will be helpful to first practice analyzing and interpreting the performance of a model.

Things we will learn from this project:

- How to use NumPy to investigate the latent features of a dataset.
- How to analyze various learning performance plots for variance and bias.
- How to determine the best-guess model for predictions from unseen data.
- How to evaluate a model's performance on unseen data using previous data.
- How to do all of the above tasks in **PySpark**.

## Description
The Boston housing market is highly competitive, and we want to be the best real estate agent in the area. To compete with our peers, we decide to leverage a few basic machine learning concepts to assist us and a client with finding the best selling price for their home. Luckily, we've come across the Boston Housing dataset which contains aggregated data on various features for houses in Greater Boston communities, including the median value of homes for each of those areas. Your task is to build an optimal model based on a statistical analysis with the tools available. This model will then be used to estimate the best selling price for our clients\' homes.

This project contains three files:

- `boston_housing.ipynb`: This is the main file containing the implementation using **Scikit-Learn**, **Pandas**, **NumPy**, and **Matplotlib**.
- `boston_housing_PySpark.ipynb`: This is the main file containing the implementation in **PySpark**.
- `housing.csv`: The project dataset. You'll load this data in the notebook.
- `visuals.py`: This Python script provides supplementary visualizations for the project.
