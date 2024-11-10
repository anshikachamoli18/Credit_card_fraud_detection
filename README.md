Credit Card Fraud Detection
This project focuses on detecting fraudulent transactions in a credit card dataset. Initially, the dataset was imbalanced, leading to high accuracy but poor fraud detection performance. Three models—Logistic Regression, Random Forest, and XGBoost—were used.

Key Insights:
Without Balancing:
Logistic Regression: 99.87% accuracy, F1 score 0.77.
Random Forest & XGBoost: 99.94% accuracy, F1 score 0.89.
With SMOTE (Dataset Balancing):
Logistic Regression: 97.57% accuracy, F1 score 0.19, AUC 0.95.
Random Forest: 99.92% accuracy, F1 score 0.87, AUC 0.91.
XGBoost: 99.87% accuracy, F1 score 0.80, AUC 0.91.
Conclusion:
Random Forest and XGBoost consistently outperformed Logistic Regression in terms of F1 score and AUC, especially after using SMOTE to handle the imbalanced dataset.
