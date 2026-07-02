# LINEAR AND LOGISTIC REGRESSION USING SCIKIT-LEARN PIPELINES

## OVERVIEW

This project demonstrates the implementation of both **Linear Regression** and **Logistic Regression** using end-to-end machine learning pipelines in Scikit-learn. The notebook covers data preprocessing, feature engineering, model training, prediction, and evaluation while following best practices to prevent data leakage.

Two datasets are used:

1. **House Prices Dataset** – Regression Task
2. **Titanic Dataset** – Classification Task

---

## OBJECTIVES

### Part A: House Prices Dataset

* Predict house sale prices using Linear Regression.
* Apply preprocessing techniques for numerical and categorical features.
* Evaluate model performance using RMSE and R² Score.
* Compare Linear Regression with Ridge and Lasso Regression.

### Part B: Titanic Dataset

* Predict passenger survival using Logistic Regression.
* Handle missing values and categorical variables through preprocessing pipelines.
* Evaluate classification performance using Classification Report, F1 Score, ROC-AUC, and Confusion Matrix.
* Interpret model coefficients to understand feature importance.

---

## TECHNOLOGIES USED

* Python
* Pandas
* NumPy
* Scikit-learn

---

## MACHINE LEARNING CONCEPTS COVERED

### Data Preprocessing

* Missing Value Imputation
* Feature Scaling
* One-Hot Encoding
* ColumnTransformer
* Scikit-learn Pipelines

### Regression Models

* Linear Regression
* Ridge Regression (L2 Regularization)
* Lasso Regression (L1 Regularization)

### Classification Models

* Logistic Regression

### Evaluation Metrics

#### Regression

* Root Mean Squared Error (RMSE)
* R² Score

#### Classification

* Classification Report
* F1 Score
* ROC-AUC Score
* Confusion Matrix

---

## WORKFLOW

### House Prices Regression Pipeline

1. Load and inspect dataset.
2. Separate features and target variable.
3. Split data into training and testing sets.
4. Identify numerical and categorical columns.
5. Create preprocessing pipelines:

   * Median imputation and scaling for numerical features.
   * Most frequent imputation and one-hot encoding for categorical features.
6. Combine preprocessing using ColumnTransformer.
7. Build Linear Regression pipeline.
8. Train model and generate predictions.
9. Evaluate performance using RMSE and R².
10. Train and compare Ridge and Lasso Regression models.

---

### Titanic Classification Pipeline

1. Load Titanic dataset.
2. Separate features and target variable.
3. Perform stratified train-test split.
4. Identify numerical and categorical features.
5. Create preprocessing pipelines.
6. Build Logistic Regression pipeline.
7. Train classification model.
8. Generate predictions and probability scores.
9. Evaluate model using:

   * Classification Report
   * F1 Score
   * ROC-AUC Score
   * Confusion Matrix
10. Analyze feature importance through model coefficients.

---

## KEY LEARNINGS

* Building reusable machine learning pipelines.
* Preventing data leakage by fitting preprocessing only on training data.
* Handling mixed numerical and categorical datasets efficiently.
* Applying regularization techniques to regression models.
* Evaluating classification models using multiple performance metrics.
* Interpreting model coefficients for business insights.

---

## CONCLUSION

This project demonstrates how Scikit-learn Pipelines and ColumnTransformer can be used to create clean, scalable, and production-ready machine learning workflows. The House Prices dataset showcases regression techniques, while the Titanic dataset demonstrates binary classification using Logistic Regression. Together, they provide practical experience with preprocessing, model training, evaluation, and interpretation in real-world machine learning tasks.


