Advanced Pattern Recognition: Assignment 1
Project Title: Wine Cultivar Classification using Linear Discriminant Analysis
Author: Hemanth

Course: Advanced Pattern Recognition (APR)

Date: 19 September 2025

1. Overview
This project is a submission for Assignment 1 of the Advanced Pattern Recognition course. The goal is to apply a pattern recognition algorithm to a real-world dataset, demonstrate its implementation, and evaluate its performance.

The chosen task is to classify different cultivars of wine using the Wine Recognition Dataset sourced from Kaggle. The algorithm implemented is Linear Discriminant Analysis (LDA), a classical supervised learning technique well-suited for this multi-class classification problem. The project demonstrates the full machine learning workflow, from data preprocessing and model training to evaluation and visualization.

2. Dataset
The dataset used is the Wine Recognition Dataset from Kaggle's wineuci collection.

Source: Kaggle: wineuci Dataset

File: Wine.csv

Features: The dataset contains 13 chemical and physical properties of the wines.

Target: The target variable is the wine's cultivar, divided into three distinct classes.

3. Algorithm: Linear Discriminant Analysis (LDA)
Linear Discriminant Analysis is a dimensionality reduction and classification algorithm. It works by finding the linear combinations of features that best separate the classes in the dataset. LDA assumes that the data is normally distributed and that the classes share the same variance. For this project, LDA was chosen to demonstrate its effectiveness in finding a clear linear boundary between the three wine classes.

4. Files in this Repository
Assignment_1.ipynb: The main Jupyter Notebook containing all the Python code, including data loading, preprocessing, model implementation, evaluation, and visualization.

README.md: This file, providing an overview of the project.

Report.pdf: (You will create this) A detailed report documenting the project's methodology, results, and discussion.

Wine.csv: The dataset file required to run the notebook.

5. How to Run the Code
To run the code, you must first set up a Python virtual environment with the required libraries.

1. Clone the Repository:

Bash

git clone https://github.com/hemanthreddar/APR_Assignments/
cd APR_Assignments/
2. Download the Dataset:
Make sure you have downloaded the Wine.csv file from the Kaggle link provided above and placed it in the APR_Assignments directory.

3. Set up the Environment (using conda):

Bash

conda create -n apr_env python=3.10
conda activate apr_env
pip install scikit-learn pandas matplotlib jupyter
4. Launch Jupyter and Run the Notebook:

Bash

jupyter notebook
Open Assignment_1.ipynb in your browser and run all the cells in the notebook. The code will execute the full analysis and generate the output and plots.
