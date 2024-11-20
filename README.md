# Classification
## Overview
This project demonstrates the classification of emails into different categories using machine learning models. The dataset is preprocessed, and various classifiers such as Logistic Regression, Decision Tree, Support Vector Machine (SVM), and Random Forest are evaluated for performance. The best-performing model is then fine-tuned using hyperparameter optimization.

## Features
- Data preprocessing including handling missing values, scaling, and encoding.
- Implementation of four classification models:
  - Logistic Regression
  - Decision Tree Classifier
  - Support Vector Machine (SVM)
  - Random Forest Classifier
- Cross-validation for model evaluation.
- Hyperparameter tuning using GridSearchCV for the best-performing model.
- Performance metrics: Accuracy, Precision, Recall, F1 Score, and Classification Report.

## Dataset
The dataset (`emails.csv`) contains features related to emails and a target column (`Prediction`) for classification. Note: Replace the column names with your dataset's specific column names if different.

### Preprocessing Steps
1. Dropped non-informative columns (e.g., 'Email').
2. Handled missing values (if any).
3. Scaled numerical features using `StandardScaler`.
4. Split data into training and testing sets (80-20 split).

## Installation and Setup
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_folder>
