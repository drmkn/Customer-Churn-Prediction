# Customer Churn Prediction
This project implements a predictive model to identify customers likely to churn. It explores two approaches for handling class imbalance: Stratified Sampling and Synthetic Minority Oversampling Technique (SMOTE). The performance of different machine learning models is evaluated based on precision, recall, F1-score, and accuracy. Additionally, Grid Search is employed to optimize hyperparameters for the models.

## Key Features
- Data Loading: Utilizes the [Churn for Bank Customers Dataset](https://www.kaggle.com/datasets/mathchi/churn-for-bank-customers/data)
 from Kaggle for training and testing.
- Handling Class Imbalance:
   - Stratified Sampling: Maintains the natural distribution of classes in the dataset.
   - SMOTE: Oversamples the minority class to balance the dataset.
- Machine Learning Models:
   - Logistic Regression
   - Random Forest Classifier
   - XGBoost Classifier
- Hyperparameter Tuning:
   - Grid Search: Conducts an exhaustive search over specified hyperparameter values to improve model performance.
- Evaluation Metrics:
   - Precision
   - Recall
   - F1 Score
   - Accuracy
 
## Summary of Results
- Stratified Sampling:
  - Logistic Regression: F1-score of 0.56.
  - Random Forest: F1-score of 0.59.
  - XGBoost Classifier: F1-score of 0.63.
- SMOTE:
  - Logistic Regression: Improved F1-score to 0.59.
  - Random Forest: Slightly improved F1-score to 0.60.
  - XGBoost Classifier: Maintained F1-score of 0.63.

