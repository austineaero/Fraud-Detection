# Fraud-Detection

This is my solution to the Kaggle Credit Card Fraud Detection challenge. The credit card data was obtained from
https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud

The dataset contains transactions made by credit cards in September 2013 by European cardholders.
The machine learning algorithm - XGBClassifier - was selected for this project. With some hyperparameter tuning it was able to achieve great results, one of which is depicted in the confusion matrix below.


![cm](https://user-images.githubusercontent.com/66695888/219818292-0b27ae50-ea4c-4772-b75d-d4946dcdd89d.png)

While the number of false positives (FP) is relatively low (i.e. 2), the number of false negatives (FN) is high (i.e. 19) which means those fraudulent activities would have passed through the system. This will most likely resort to loss of money, loss of customers or a negative customer experience. 

Therefore, future work will focus on trying to reduce the number of FN without overfitting the data using a deep learning model.
