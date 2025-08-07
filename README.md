Iris Species Classification
Project Overview
This project focuses on the classic Iris dataset to demonstrate fundamental machine learning concepts, including data cleaning, visualization, and model building. The primary objective is to classify the species of iris flowers into one of three categories: Iris-setosa, Iris-versicolor, and Iris-virginica.

Dataset
The dataset used in this project is the Iris data set, collected from Kaggle. It includes 150 instances with 4 features:

SepalLengthCm

SepalWidthCm

PetalLengthCm

PetalWidthCm

The dataset is perfectly balanced, with 50 instances for each species. The Id column was dropped during the data cleaning phase as it was not needed for the analysis.

Analysis and Methodology
The project followed a standard machine learning workflow:

Data Loading and Initial Exploration: The dataset was loaded using pandas, and initial checks were performed to understand its structure and content.

Data Cleaning: The Id column was removed, and null values were checked for, confirming there were none.

Data Visualization: Visualizations were created to explore the relationships between features and to understand the distribution of the data.

Model Building: Two classification algorithms were implemented and evaluated:

Logistic Regression: A linear model used to predict the probability of a categorical outcome.

K-Nearest Neighbors (K-NN) Classifier: A non-parametric method used for classification and regression.

Model Evaluation: Both models were trained and tested, with the K-Nearest Neighbors classifier achieving an accuracy of 97.77%.

Technologies and Libraries Used
Python: The core programming language.

Pandas: For data manipulation and analysis.

NumPy: For numerical operations.

Matplotlib: For creating static, animated, and interactive visualizations.

Seaborn: For statistical data visualization.

Scikit-learn: For machine learning models and evaluation metrics.

Jupyter Notebook: The development environment for the project.

How to Run
Clone this repository.

Install the required libraries:

Bash

pip install pandas numpy matplotlib seaborn scikit-learn
Open the Jupyter Notebook Iris data.ipynb and run the cells.
