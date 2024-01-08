# Loan-Payoff

In this notebook we use the dataset about past loans , do feature engineering and implement the classification algorithms namely - KNN, DecisionTree,SVM and Logistic Regression. Also we find the best model based on evaluation metrics namely - jaccard index, F1 Score and LogLoss.

We load a dataset using Pandas library. This dataset is about past loans. The Loan_train.csv data set includes details of 346 customers whose loan are already paid off or defaulted. It includes following fields:

![image](https://github.com/divyasingh13/LoanPayoff/assets/43674640/239e77cd-aa36-4fc6-95e6-913e80cbb3a0)


Data Preprocessing:
  
260 people have paid off the loan on time while 86 have gone into collection. Lets plot some columns to underestand data better:

![image](https://github.com/divyasingh13/LoanPayoff/assets/43674640/cfe59a1c-5f18-486f-8d57-ae8c6caf7d4d)


Lets look at the day of the week people get the loan:

![image](https://github.com/divyasingh13/LoanPayoff/assets/43674640/c2b6fbca-4fef-48db-8f9b-c463a11e65f7)


One hot Encoding :

![image](https://github.com/divyasingh13/LoanPayoff/assets/43674640/8bc59e70-2c84-4a74-b36e-8a81f2fbef54)


Classification :

1. KNN -The k-nearest neighbors algorithm, also known as KNN or k-NN, is a non-parametric, supervised learning classifier, which uses proximity to make classifications or predictions about the grouping of an individual data point. While it can be used for either regression or classification problems, it is typically used as a classification algorithm, working off the assumption that similar points can be found near one another.

2. Decision Trees- A decision tree is a non-parametric supervised learning algorithm, which is utilized for both classification and regression tasks. It has a hierarchical, tree structure, which consists of a root node, branches, internal nodes and leaf nodes.

3. SVM - Support vector machines (SVMs) are a set of supervised learning methods used for classification, regression and outliers detection.SVM works by mapping data to a high-dimensional feature space so that data points can be categorized, even when the data are not otherwise linearly separable.

4. Logistic Regression - Logistic regression is a process of modeling the probability of a discrete outcome given an input variable. The most common logistic regression models a binary outcome; something that can take two values such as true/false, yes/no, and so on.

Evaluation Metrics:

![image](https://github.com/divyasingh13/LoanPayoff/assets/43674640/a91f6134-1a07-4669-bae4-49e7ffe7e7b8)


