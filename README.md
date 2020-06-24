# Kaggle competition: Santander Customer Transaction Prediction
Project made with the purpose of studying the optimization of hyperparameters with Skopt

[Check the competition here!](https://www.kaggle.com/c/santander-customer-transaction-prediction)

 **Description**

> "At [Santander](https://www.santanderbank.com) our mission is to help people and businesses prosper. We are always looking for ways to help our customers understand their financial health and identify which products and services might help them achieve their monetary goals.
Our data science team is continually challenging our machine learning algorithms, working with the global data science community to make sure we can more accurately identify new ways to solve our most common challenge, binary classification problems such as: is a customer satisfied? Will a customer buy this product? Can a customer pay this loan?
In this challenge, we invite Kagglers to help us identify which customers will make a specific transaction in the future, irrespective of the amount of money transacted. The data provided for this competition has the same structure as the real data we have available to solve this problem."

 **Techniques Utilized:**
 - Undersampling (Near miss)
 - Scikit-optimize (gp_minimize)
 - Variables selection (by f_classif)

 **Models:**
 - SGD Classifier
 - XGBoost Classifier
 - LGBM Classifier

**Submissions Scores:**
|Model|  ROC AUC|
|--|--|
|SGD Classifier|0.85651|
|XGBoost Classifier|0.86762|
|LGBM Classifier|0.87939|


