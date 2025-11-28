# Developers_Hub_Internship-Task2-
## Task 2: Heart Disease Prediction

### Objective
Predict whether a patient has heart disease using clinical and demographic data.

### Dataset
- CSV dataset with features such as age, sex, chest pain type, blood pressure, cholesterol, fasting blood sugar, etc.
- Target variable: `num` (1 = disease, 0 = no disease).

### Data Preprocessing
- Converted `num` to binary (disease/no disease).
- Encoded categorical features using Label Encoding.
- Handled missing values automatically.
- Split data into training (80%) and testing (20%) sets.

### Model Applied
- Logistic Regression

### Model Evaluation
- Accuracy Score
- Confusion Matrix
- ROC Curve & AUC

### Insights
- Logistic Regression provides a simple yet effective baseline for disease classification.
- Features such as chest pain type, blood pressure, and cholesterol strongly influence predictions.

### Notebook
- `heart_disease_prediction.ipynb`

---
