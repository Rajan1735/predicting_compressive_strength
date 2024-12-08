Predicting Compressive Strength of Ultra-High-Performance Concrete (UHPC)
This project explores the use of deep learning techniques to predict the compressive strength (CS) of Ultra-High-Performance Concrete (UHPC) based on its mixture proportions and curing conditions. The dataset contains various features related to the composition and properties of UHPC, with CS as the target variable.

Project Overview
What I Did:
Data Loading and Exploration:

Uploaded and explored the UHPC dataset containing 14 features and the target (CS).
Analyzed the data for missing values, descriptive statistics, and feature distributions.
Data Preprocessing:

Split the dataset into training, validation, and test sets (70-15-15 split).
Normalized the feature data using StandardScaler to ensure all features contribute equally during training.
Model Development:

Built a feedforward neural network using TensorFlow/Keras with three hidden layers.
Used Mean Squared Error (MSE) as the loss function and Mean Absolute Error (MAE) as the evaluation metric.
Trained the model with early stopping to prevent overfitting and ensure optimal performance.
Model Evaluation:

Evaluated the trained model on the test set.
Visualized the model’s performance by plotting the actual vs. predicted compressive strength values.
Results Visualization:

Plotted the training and validation loss over epochs to analyze convergence.
Scatter plot of actual vs. predicted compressive strength.
data source:https://data.mendeley.com/datasets/85r7bh4zsz/1

