# ***credit-card-fraud-prediction***
***Credit Card Fraud Prediction using Logistic Regression, Random Forest and XGBoost Classifier***

This is coparison based training model for three different machine learning algorithms - Logistic Regression, Random Forest and XG Boost.

At first, we have trained the whole dataset without any preprocessing with all these models. Then we applied both under sampling and over sampling (SMOTE) to the train set of the data.

Then we have validated our trained model using Kfold Cross Validation, Confusion Matrix, GridSearch Cross Validation, ROC Curve, Precesion and Recall scores.

At last, we have compared all these models only on the under sampled data(Because it gave us the best output so far) and found that the XG Boost model worked best for this dataset!


### ***Here is the graph of the AUC Curve of the model comparison***

![download](https://user-images.githubusercontent.com/65129467/118031921-e1ca7c80-b388-11eb-84e0-b84c0081d096.png)

