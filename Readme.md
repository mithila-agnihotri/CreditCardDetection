# Fraud Detection
## Analysis of creditcard transactions in order to predict fraudulent ones. 
First I used an SVM Classifier with the default kernel -RBF without any feature scaling for prediction. I got an AUC(of ROC) score of 0.95. 
Then I tried an SVM Classifier again with the default kernal (RBF), but with minmax scaling on the features. This time I got a slightly better AUC score of 0.96.
Then I used GridSearchCV to tune the gamma parameter using roc_auc as the scoring parameter, but it turned out the default paramters were the best as my best score was still 0.96.

I also tried a linear SVM Classifier


