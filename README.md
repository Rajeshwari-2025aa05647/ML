
# ML Assignment 2 – Classification Models Deployment

## a. Problem Statement
The objective of this assignment is to implement multiple machine learning classification models on a single dataset, evaluate their performance using standard metrics, and deploy the models through an interactive Streamlit web application.

## b. Dataset Description
The dataset used is the Heart Disease UCI dataset obtained from a public repository.
- Type: Binary Classification
- Number of instances: 920
- Number of features: 15
- Target variable: num (converted to binary: 0 = No disease, 1 = Disease)

## c. Models Used and Evaluation Metrics

The following six classification models were implemented and evaluated on the same dataset:

| ML Model | Accuracy | AUC | Precision | Recall | F1 Score | MCC |
|---------|----------|-----|-----------|--------|----------|-----|
| Logistic Regression | 0.8478 | 0.9189 | 0.8426 | 0.8922 | 0.8667 | 0.6913 |
| Decision Tree | 0.8370 | 0.8338 | 0.8462 | 0.8627 | 0.8544 | 0.6694 |
| KNN | 0.8315 | 0.8949 | 0.8447 | 0.8529 | 0.8488 | 0.6586 |
| Naive Bayes | 0.8261 | 0.8775 | 0.8365 | 0.8529 | 0.8447 | 0.6473 |
| Random Forest | 0.8967 | 0.9500 | 0.8807 | 0.9412 | 0.9100 | 0.7916 |
| XGBoost | 0.8804 | 0.9399 | 0.8704 | 0.9216 | 0.8952 | 0.7579 |

## d. Observations on Model Performance

| ML Model | Observation |
|--------|-------------|
| Logistic Regression | Performed well on linearly separable data but struggled with complex patterns |
| Decision Tree | Showed tendency to overfit the training data |
| KNN | Performance was sensitive to feature scaling |
| Naive Bayes | Fast and efficient but limited by independence assumption |
| Random Forest | Delivered strong and stable performance due to ensemble learning |
| XGBoost | Achieved the best overall performance with high predictive accuracy |
