# Healthcare Expenses Prediction
This Python script uses machine learning to predict healthcare expenses based on various features. It uses the Keras library to build and train a neural network model.

## Data Preprocessing
The dataset includes features like 'smoker' and 'region', which are mapped to numerical values for processing. The dataset is split into an 80/20 train/test split. The 'expenses' column is separated to create labels for training and testing.

## Model Training
The training data is normalized and a sequential model is defined with three dense layers and a final output layer. The model uses the Adam optimizer and is trained to minimize the Mean Absolute Error (MAE) between the predicted and actual expenses.

This script provides a starting point for regression tasks using neural networks. Further tuning and experimentation can improve the model's performance.

![image](https://github.com/aguspatur22/Linear-Regression-Health-Costs-Calculator/assets/50930830/6f98f5da-93f9-4d5f-a37c-326aec8ae3c9)
