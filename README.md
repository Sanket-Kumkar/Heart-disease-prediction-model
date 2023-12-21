# Heart-disease-prediction-model

This notebook explores the use of various Python-based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting whether or not someone has heart disease based on their medical attributes.

The data is acquired in the form of a CSV file from a machine learning repository with the help of 'Kaggle' (a platform for data science competitions) and passed as input.

Three machine learning models are used:

Logistic Regression.
K-Nearest Neighbors Classifier.
Random Forest Classifier.
The function 'fit_and_score' goes through all three models, fits the model, and tests scores as well.

Hyperparameter tuning is done with RandomizedSearchCV.

Evaluation of the tuned model is done with:

ROC curve and AUC score
Confusion matrix
Classification report
Precision
Recall
F1 score
