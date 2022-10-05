CREDIT CARD FRAUD DETECTION MODEL (Using Logistic Regression, KNN, Kernel SVM, Naive Bayes, Decision Tree and Random Forest)

A model that classifies credit card transactions into "no fraud" and "fraud" categories. These models can be useful for credit card companies as they let you differentiate between a fraud and a normal transaction. Hence, they can help in determining whether an induvidual must be charged for an item they did or did not purchase. 

The dataset used to develop this model is available at, https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud. The dataset contains information on "Time", "Amount" and "Class". Other features from V1 to V28 have been transformed using PCA due to confidentiality issues. 

1. "Time" is the time between each transaction and first transaction in the dataset and is available in seconds. 
2. "Amount" is the amount transacted. 
3. "Class" contains 0 to indicate "no fraud" and 1 to indicate "fraud". 

Also, the dataset is highly imbalanced. Meaning it has only 492 "frauds" out of the 284,807 transactions. To overcome this issue, SMOTE (Synthetic Minority Oversampling Technique) has been used, which simply duplicates the minority class i.e., "frauds", to balance both the classes. 

The following six models have been built, trained and tested: 
1. Logistic Regression Classifier
2. KNN Classifier
3. Kernel SVM Classifier
4. Naive Bayes Classifier
5. Decision Tree Classifier
6. Random Forest Classifier

The models are evaluated and compared using "confusion matrix" (a table used to understand the performance) and "accuracy scores". 
