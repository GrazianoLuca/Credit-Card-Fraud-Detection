# Credit-Card-Fraud-Detection
This Credit Card Fraud Detection project has been developed to get a practical introduction to the Sklearn library and find the best solution to a classification problem to identify credit card fraud.

The metric used is "Recall" since the purpose of the model is to find all possible cases of fraud and because we prefer having few false positives rather than missing possible fraud cases.

The project follows the preparation of three models:
  - logistic regression model
  - decision tree classifier
  - neural network model

### Logistic Regression
The model used is a Logistic Regression with varying parameters, due to the fact that the dataset is highly unbalanced and the fraud cases could be considered as outliers.

The resulting confusion matrix shows that the model has succesfully managed to spot most fraud cases and only missed 5 of them. In addition, the model has resulted in 21 false negatives which could easily be checked by a human operator, since the number is not that high, to properly classify them as non-fraud.

### Decision Tree Classifier
The second model that has been used is a Decision Tree Classifier using the gini impurity measure in an attempt to getter better fit performance.

The resulting confusion matrix shows that the model has succesfully managed to spot most fraud cases and only missed 4 of them. In addition, the model has resulted in 9 false negatives which could easily be checked by a human operator, since the number is not that high, to properly classify them as non-fraud.

