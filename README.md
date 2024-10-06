# Loan_Approval_Classifier
## Overview
This project leverages machine learning to automate loan application approval, reducing manual errors, improving decision speed, and enhancing accuracy. By processing credit and personal data, the model predicts the creditworthiness of applicants.

## Project Steps

1. CRISP-DM Framework
Followed Cross-Industry Standard Process for Data Mining: business understanding, data understanding, data preparation, modeling, evaluation, and deployment.

2. Problem Definition
Objective: Efficiently predict loan approvals using machine learning to improve accuracy, reduce processing costs, and ensure unbiased decision-making.

3. Dataset
Sourced from Kaggle, containing personal and credit details of applicants.
Merged two datasets on applicant ID: application_record.csv (personal details) and credit_record.csv (credit history).

4. Data Exploration & Preprocessing
Visualized data distributions using pie charts and histograms.
Managed missing values, encoded categorical variables, normalized numerical columns, and balanced the target variable for binary classification.

5. Modeling & Evaluation
Machine Learning Models Implemented:

Logistic Regression: Employed K-Fold Cross Validation and Holdout methods.

Random Forest: Achieved highest accuracy of 78.35%.

Naive Bayes: Moderate performance, good sensitivity.

Decision Tree: Recursive partitioning for decision-making, 65.36% accuracy.

Support Vector Machine (SVM): Low accuracy with imbalanced target variable.

Quadratic Discriminant Analysis (QDA): Improved accuracy for imbalanced classes.

Evaluation Metrics: Accuracy, confusion matrix, AUC-ROC curve, precision, recall, sensitivity, and specificity.

6. Results & Conclusion

Best Performing Model: Random Forest (78.35% accuracy).
Further improvements suggested include balancing classes, refining features, and testing more advanced models.

7. Technologies Used
Languages: R
Libraries: caret, rpart, e1071
Tools: Jupyter Notebook, RStudio

8. Future Work
Explore model improvement through class balancing, feature selection, and model optimization.
Evaluate performance with more advanced algorithms or ensemble learning techniques.
