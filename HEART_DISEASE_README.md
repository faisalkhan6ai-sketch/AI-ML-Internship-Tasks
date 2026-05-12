Task 2: Heart Disease Prediction
Organization: DevelopersHub Corporation  
Intern:Faisal Imtiaz  

Objective:
To build a machine learning model that predicts whether a person is at risk of heart disease based on clinical parameters such as age, sex, chest pain type, blood pressure, and cholesterol levels.

Dataset:
Name:Heart Disease UCI
Source:Kaggle / UCI Machine Learning Repository
Size:303 rows, 14 columns
Target:target(0 = No disease, 1 = Disease)

Workflow:
1. Data Cleaning: Handled categorical encoding and checked for null values.
2. EDA: Analyzed correlations between features like `thalach` (max heart rate) and the presence of disease.
3. Modeling: Implemented Logistic Regression classifiers.
4. Evaluation: Measured performance using a Confusion Matrix and ROC-AUC score.

 Key Findings
* Feature Importance:Chest pain type (cp) and maximum heart rate (thalach) were the most significant predictors.
* Model Performance:58.06451612903226
