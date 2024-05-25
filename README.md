# Diabetes-Dataset-Algorithm-analysis
This project investigates the impact of different missing data imputation methods on the performance of various machine learning algorithms in predicting diabetes. The comparison of KNN imputation and mean imputation techniques and analyze their effects on model accuracy using  Diabetes Database
Objectives-
Assess the impact of KNN and mean imputation on model performance.
Compare the sensitivity of various machine learning algorithms to these imputation methods.
Provide best practices for handling missing data in predictive modeling.

Dataset-
Pima Indians Diabetes Database: Contains medical predictor variables and a target variable indicating diabetes diagnosis.

Methodology-
Data Imputation:
KNN Imputer
Mean Imputer

Machine Learning Algorithms:(classification)
Logistic Regression
K-Nearest Neighbors (KNN)
Decision Tree
Random Forest
Naive Bayes
Support Vector Machine (SVM)

Model Evaluation:
Accuracy comparison between imputation methods.

Results
KNN and Logistic Regression significantly improved with mean imputation.
Decision Trees showed consistent performance with both methods.
Random Forests had mixed results; larger ensembles benefited more from mean imputation.
Naive Bayes and SVM showed robustness, with Naive Bayes performing better with mean imputation.

Conclusion
The choice of imputation method can significantly affect model performance. Mean imputation often provides more stable and improved results compared to KNN imputation.
