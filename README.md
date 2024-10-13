# Credit Card Fraud Detection
A project that explores machine learning techniques for detecting fraudulent transactions in an imbalanced dataset. This repository demonstrates data balancing techniques and classification models to improve fraud detection.

# Dataset
Source: [Credit Card Fraud Detection Dataset on Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud)
Details: Contains 284,807 transactions, where 492 are fraudulent (0.172% of the dataset).

Project Steps

Data Exploration:
Basic analysis and visualization of the distribution of fraud vs. non-fraud cases.
Scaling features and preparing training/test datasets.
Balancing Techniques:

Random Undersampling: Reduces non-fraud samples to balance the dataset.
SMOTE (Synthetic Minority Over-sampling Technique): Generates synthetic samples for the minority class to improve model performance.
Modeling:

# Classifiers Used:
Logistic Regression
K-Nearest Neighbors (KNN)
Support Vector Machine (SVM)
Decision Tree

# Neural Network (Keras)
Neural Network Structure:
Input Layer: Nodes equal to feature count.
Hidden Layer: 32 nodes with ReLU.
Output Layer: Binary classification (fraud/non-fraud).

# Evaluation Metrics:
Precision: Measures accuracy of fraud predictions among flagged cases.
Recall: Measures how well the model captures fraud cases.
F1 Score: Balances precision and recall.
Precision-Recall Curve: Evaluates the tradeoff between precision and recall for imbalanced data.

# Results
Models were evaluated based on confusion matrix, precision, recall, and F1 score. The neural network with SMOTE showed promising results in balancing recall and precision.

# Key Takeaways
Balancing Techniques like SMOTE and undersampling are essential for handling imbalanced data in fraud detection.
Evaluation Metrics such as precision and recall offer a better understanding than accuracy alone in imbalanced datasets.

# Conclusion
This project highlights the importance of using data balancing methods and precision-recall metrics in fraud detection tasks, providing a robust approach for similar imbalanced classification problems.
