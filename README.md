# credit-risk-classification
### Overview
I am training and assessing a model based on loan risk. Using historical lending data to train and test a model that identifies the creditworthiness of borrowers.

### Logistic Regression Model with the Original Data
- Accuracy: 0.9442676901753825
- Precision: array([[18679,    80],[   67,   558]])
- Recall scores of model: 0: 1.00, 1: 0.89

### Logistic Regression Model with Resampled Training Data
- Accuracy: 0.9959744975744975
- Precision: array([[18668,    91],[    2,   623]])
- Recall scores of model: 0: 1.00, 1: 1.00

<!-- Summarize the results from the machine learning model. Include your justification for recommending the model for use by the company. If you don’t recommend the model, justify your reasoning. (10 points) -->
### Summary
Between the two models, the logistic regression model using resampled data preformed best. I would recomment using the Logistic Regression Model with Resampled Training Data