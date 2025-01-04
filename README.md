# Data Mining Project: Diabetes Prediction

## Project Overview
This project focuses on building a machine learning model to predict diabetes based on various health indicators. The dataset is preprocessed, engineered, and normalized to create an effective prediction system. The primary goal is to classify individuals as diabetic or non-diabetic using advanced machine learning techniques.

---

## Features and Dataset
### Dataset Columns:
- `age`: Age of the individual.
- `hypertension`: Whether the individual has hypertension (0/1).
- `heart_disease`: Whether the individual has heart disease (0/1).
- `smoking_history`: Smoking habits of the individual.
- `bmi`: Body Mass Index.
- `HbA1c_level`: Hemoglobin A1c level.
- `blood_glucose_level`: Blood glucose level.
- `diabetes`: Target variable (1 = diabetic, 0 = non-diabetic).
- `age_group`: Categorized age group (`Child`, `Adult`, `Old`).
- `gender_Female`, `gender_Male`, `gender_Other`: Gender indicators.
- `bmi_category`: BMI classification (`Underweight`, `Normal weight`, `Overweight`, `Obese`).
- `HbA1c_above_6_5`: Indicator for HbA1c above 6.5.
- `blood_glucose_above_126`: Indicator for blood glucose above 126.

### Data Preprocessing:
1. Converted categorical columns (`smoking_history`, `age_group`, `gender`, `bmi_category`) into numerical values.
2. Balanced the dataset to ensure a diabetic proportion of 13%.
3. Normalized numerical columns to improve model performance.

---

## Machine Learning Models
### Models Implemented:
1. **CatBoost Classifier**: Handles categorical data efficiently.
2. **Random Forest Classifier**: Trained on the engineered and balanced dataset.
3. **Logistic Regression Classifier**: Trained on the engineered and balanced dataset.

---

## Technologies Used
- **Programming Language**: Python
- **Machine Learning Frameworks**: Scikit-learn, CatBoost
- **Data Manipulation**: Pandas, NumPy
- **Visualization**: Matplotlib, Seaborn

---

## Author
- **Oussama Tazi** 
- **Houssam EL AZAMI EL IDRISSI**  

---
