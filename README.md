# Credit-risk-classification
Overview of the Analysis

This analysis aims to develop a machine learning model that accurately predicts a borrower's creditworthiness. The financial dataset includes various borrower characteristics, such as loan size, interest rate, income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. These features will help determine whether granting a loan poses a significant risk.

The target variable is to classify loans as high-risk or not.

Methodology

The dataset was divided into training and testing subsets using the train_test_split function. We selected logistic regression for the classification of loan risk. The model was trained on the training data, and predictions were made on the test set. To evaluate the model's performance, we calculated accuracy, precision, and recall through a confusion matrix and classification report.

Results

Logistic Regression Learning Model:

Accuracy score: 0.99

Precision scores:

0 (healthy loan): 1.00
1 (high-risk loan): 0.84

Recall scores:

0 (healthy loan): 0.99
1 (high-risk loan): 0.94


Accuracy: The model achieved an accuracy score of 0.992, indicating that 99% of its predictions were correct.

Precision: The precision score for healthy loans was 1.00, reflecting perfect accuracy. Conversely, the precision for high-risk loans was 0.84, which means 84% of loans labeled as "high-risk" were indeed high-risk, while 16% were false positives.

Recall: The recall for healthy loans stood at 0.99, suggesting that 99% of actual healthy loans were correctly identified. In contrast, the recall for high-risk loans was 0.94, meaning the model correctly identified 94% of true high-risk loans, missing only 6% (false negatives).

Summary

The Logistic Regression model demonstrated 99% accuracy, with a commendable recall of 94% for high-risk loans, showcasing its reliability in identifying risky cases. While the precision for high-risk loans is 84%, the high recall indicates effective risk detection. Given its overall performance,  this model is highly recommended for effectively identifying high-risk loans.
