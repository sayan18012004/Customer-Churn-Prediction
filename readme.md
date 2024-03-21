# Customer Churn Prediction

This repository contains code for predicting customer churn using a neural network model built with TensorFlow. Customer churn prediction is a vital task for businesses to understand and mitigate customer attrition, ultimately improving customer retention and business performance.

## Dataset

The dataset used for this project is "Churn-Data.csv", which contains various features related to customer behavior, demographics, and services subscribed. It includes information such as gender, partner status, tenure, internet service type, contract details, and churn status.

## Data Preprocessing

- Loaded the dataset from the CSV file.
- Performed exploratory data analysis (EDA) to understand the data distribution and relationships.
- Handled missing values and encoded categorical variables.
- Scaled numerical features using MinMaxScaler.

## Model Building

- Constructed a neural network model using TensorFlow's Keras API.
- The model architecture consists of input layers, hidden layers with ReLU activation, and an output layer with sigmoid activation.
- Compiled the model with binary cross-entropy loss function and Adam optimizer.

## Model Training and Evaluation

- Split the dataset into training and testing sets.
- Trained the model on the training data for a specified number of epochs.
- Evaluated the trained model on the test data using the evaluate method.
- Calculated F1 score as an additional performance metric using a custom TensorFlow function.

## Results

- Achieved an accuracy of 72% on the test data.
- Obtained an F1 score of 0.72 using TensorFlow's custom function.

## Model Saving
The trained model is saved to a file named 'model.h5' in the model folder for future use.