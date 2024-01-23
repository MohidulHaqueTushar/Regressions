# Concept of Regressions

Regression modles generally used to predict continuous data. There are many kinds of regression problems available to deal with different types of problems. <br>

## Common Regression Types:
1. Linear Regression
2. Polynomial Regression
3. Regularized Regression
     1. Ridge Regression
     2. Lasso Regression
     3. Elastic Net Regression
     4. Early Stopping
4. Logistic Regression

### Model Training
Regression models can be trained in two different ways:
1. Closed Form: where the data have low complexity, less training features, and less data points
2. Gradient Descent: where the problem has wide range, complex, more training features, and more training instances <br>
  There are three versions of GD:
    1. Batch Gradient Descent
    2. Stochastic Gradient Descent
    3. Mini-batch Gradient Descent

### Model Accuracy
To access accuracy, that the model is overfitting or underfitting the training data, we can use the following concepts:
  1. Cross-Validation
  2. Learning Curves

