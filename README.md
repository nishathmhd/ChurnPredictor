
# Bank Customer Churn Prediction

## Overview
This repository contains code for predicting customer churn in a bank using machine learning. The project involves data exploration, preprocessing, and building a predictive model using a neural network.

## Datasets
- **sample_submission.csv**: Sample submission file for the competition.
- **test.csv**: Test dataset containing customer information.
- **train.csv**: Training dataset with information about customer churn.

## Data Exploration and Analysis (EDA)
- Explored datasets to understand feature distributions, identify missing values, and visualize relationships.
- Examined the distribution of the target variable ('Exited') to understand class balance.

## Data Preprocessing
- Handled missing values and outliers in the data.
- Processed 'Tenure' column to handle negative values.
- Converted categorical variables ('Geography' and 'Gender') into numerical representations using one-hot encoding.

## Machine Learning Model
- Built a simple Artificial Neural Network (ANN) using TensorFlow and Keras.
- Standardized numerical features and split the data into training and testing sets.
- Trained the model and evaluated its performance using classification metrics.

## Results
- Achieved an accuracy of [your_accuracy_score] on the test set.
- Classification Report, Confusion Matrix, and other metrics are provided for detailed evaluation.

## Instructions
1. Clone the repository: `git clone [repository_url]`
2. Install the required libraries: `pip install -r requirements.txt`
3. Run the Jupyter Notebook `churn_prediction.ipynb` for detailed analysis and model training.

Feel free to explore, contribute, or provide feedback!


