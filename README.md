# AI-ML-Task3-House-Price-Prediction
AI/ML project demonstrating overfitting analysis, 5-fold cross-validation, GridSearchCV hyperparameter tuning, and model optimization for house price prediction.

## Model Validation, Overfitting Detection & Hyperparameter Tuning

### Project Overview

This project demonstrates industry-standard machine learning validation and optimization techniques using the California Housing Dataset.

The objective was to improve model reliability through:

* Overfitting Detection
* Cross Validation
* Hyperparameter Tuning
* Model Comparison
* Final Model Selection

---

## Dataset

The California Housing Dataset contains:

* Median Income
* House Age
* Average Rooms
* Average Bedrooms
* Population
* Latitude
* Longitude

Target Variable:

* House Price

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook
* Joblib

---

## Project Workflow

1. Data Loading
2. Data Preprocessing
3. Feature Scaling
4. Train-Test Split
5. Overfitting Detection
6. Cross Validation
7. GridSearchCV Optimization
8. Model Evaluation
9. Model Comparison
10. Final Model Selection

---

## Overfitting Analysis

The baseline Decision Tree model achieved:

* Train RMSE ≈ 0.000
* Test RMSE ≈ 0.702

This significant difference indicates severe overfitting.

---

## Cross Validation

5-Fold Cross Validation was used to obtain a reliable estimate of model performance.

Cross Validation RMSE:

0.896

---

## Hyperparameter Tuning

GridSearchCV identified the following optimal parameters:

| Parameter         | Value |
| ----------------- | ----- |
| max_depth         | 10    |
| min_samples_split | 10    |

---

## Model Comparison

| Model               | RMSE     | R² Score |
| ------------------- | -------- | -------- |
| Linear Regression   | 0.745581 | 0.575788 |
| Ridge Regression    | 0.745554 | 0.575819 |
| Tuned Decision Tree | 0.645430 | 0.682099 |

---

## Best Model

🏆 Tuned Decision Tree Regressor

Reasons:

* Lowest RMSE
* Highest R² Score
* Improved Generalization
* Reduced Overfitting

---

## Results

The optimized Decision Tree outperformed all baseline models and achieved the best predictive performance.

---

## Project Deliverables

* Jupyter Notebook
* Trained Model
* Professional Report
* Screenshots
* GitHub Repository

---

## Author

Rishabh

AI & Machine Learning Internship – Task 3

