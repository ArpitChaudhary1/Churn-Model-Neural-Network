# Churn Model Neural Network

## Overview

This repository contains a neural network-based model for predicting customer churn. The model learns patterns from historical customer data and performs binary classification to estimate whether a customer is likely to leave or stay.

The implementation follows a standard machine learning workflow, including data preprocessing, model training, evaluation, and prediction using an Artificial Neural Network.


## Repository Structure

* `Churn_Modelling.csv`
  A dataset containing customer features such as demographics, account information, and activity indicators.

* `churn_model.ipynb`
  Jupyter notebook that covers data loading, preprocessing, model construction, training, evaluation, and prediction.

* `churn_model.pkl`
  Saved trained model that can be loaded directly for inference without retraining.

## Approach

1. Load and explore the dataset.
2. Encode categorical variables and scale numerical features.
3. Split the data into training and testing sets.
4. Build an Artificial Neural Network using a deep learning framework.
5. Train the model on the training data.
6. Evaluate performance on the test data.
7. Generate churn predictions for new customer samples.

## Model Output

The model produces a probability score for churn and a final binary classification:

* `1` indicates the customer is likely to churn
* `0` indicates the customer is likely to remain

## How to Run

1. Open `churn_model.ipynb` in Jupyter Notebook or VS Code.
2. Install the required Python libraries, such as:

   * numpy
   * pandas
   * scikit-learn
   * tensorflow / keras
3. Run the notebook cells in sequence to train the model and view evaluation results.

To use the trained model directly, load `churn_model.pkl` in a Python script and pass new customer data for prediction.
