# Credit-Card-Fraud-Detection
This Credit Card Fraud Detection project has been developed to get a practical introduction to the Sklearn library and prepare a classification model.

The model used is a LogisticRegression with varying parameters, due to the fact that the dataset is highly unbalanced and the fraud cases could be considered as outliers.
The used metric is "Recall" since the purpose of the model is to find all possible cases of fraud and because we prefer having few false positives rather than missing possible fraud cases.

The resulting confusion matrix shows that the model has succesfully managed to spot most fraud cases and only missed 3 of them. In addition, the model has resulted in 13 false positives which could easily be checked by a human operator to properly classify the case as non-fraud.
