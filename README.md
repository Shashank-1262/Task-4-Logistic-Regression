# **Task-4-Logistic-Regression**

1. Loads the dataset from a CSV file.
2. Cleans the data by:
      Removing unnecessary columns like ID.
      Removing empty columns.
      Dropping rows with missing target values.
3. Converts the target labels:
      Converts 'M' (Malignant) to 1
      Converts 'B' (Benign) to 0
4. Selects only numeric features for the model.
5. Splits the data into training and testing sets (80% training, 20% testing).
6. Standardizes the features so they all have the same scale.
7. Trains a Logistic Regression model on the training data.
8. Evaluates the model using:
      Confusion matrix
      Precision and recall
      ROC-AUC curve
9. Shows the sigmoid function (used by logistic regression).
10. Tests a custom threshold (e.g., 0.6) to see how it affects results.
