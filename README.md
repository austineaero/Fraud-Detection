# Fraud-Detection

This is my own solution to the Kaggle Credit Card Fraud Detection challenge. The credit card data was obtained from
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

The dataset contains transactions made by credit cards in September 2013 by European cardholders.
The machine learning algorithm - XGBClassifier - was selected for this project. With some hyperparameter tuning it was able to achieve great results, one of which is depicted in the confusion matrix below.


![cm](https://user-images.githubusercontent.com/66695888/219818292-0b27ae50-ea4c-4772-b75d-d4946dcdd89d.png)

As can be seen there are still some false positives (FP) and false negatives (FN) which may negatively impact customer satisfaction. Therefore, future work will be on trying to reduce the number of FP and FN without overfitting the data using a deep learning model.
