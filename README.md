# Title: Breast Cancer Diagnosis Models
---
## Description:
These notebooks demonstrate building and evaluating models to classify breast cancer as malignant or benign using the Wisconsin Diagnostic Breast Cancer dataset.
---
## Steps:

### Data Loading and Preprocessing:
- Load the dataset.
- Encode the target variable (Diagnosis) to numerical values (M = 1, B = 0).
- Split the dataset into features (X) and target (y).
- Split the data into training and testing sets.
- Standardize the features using StandardScaler.

### Model Training and Evaluation:
#### Model 1 (aymanbukar_model_v1.ipynb):
- Train a logistic regression model.
- Evaluate with accuracy, confusion matrix, and classification report.

#### Model 2 (aymanbukar_model_v2.ipynb):
- Train a gradient boosting model.
- Evaluate with accuracy, confusion matrix, and classification report.
- Display accuracy in percentage.