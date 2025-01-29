Dataset

The dataset used is the Wine Quality dataset, specifically the red wine subset, available in CSV format. Each record contains various chemical properties of wine, along with a target variable indicating the wine's quality (ranging from 0 to 10).

Code Structure
Data Loading and Preparation: Loads the dataset and splits it into features (X) and target variable (y).
Data Splitting: The dataset is divided into training (70%), validation (15%), and test (15%) sets using scikit-learn's train_test_split function.
Linear Regression (Closed-Form Solution): Implements linear regression using the closed-form solution to calculate weights based on the training data.
Prediction: A function to make predictions based on the learned weights.
Visualization: Generates a scatter plot comparing actual and predicted quality values for the training set.
Model Evaluation: Computes and reports the Root Mean Square Error (RMSE) for both training and test sets.
Least Mean Squares (LMS) Algorithm: Implements the LMS algorithm for training the model with random initialization of weights and a specified learning rate.

Usage

Load the dataset: Ensure the CSV file (winequality-red.csv) is in the same directory as the code or provide the correct file path.
Run the script: Execute the Python script in your preferred environment. The script will output RMSE values for both the closed-form solution and the LMS algorithm.
