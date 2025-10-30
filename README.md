# heart-disease-simple
A simple ml project that predicts the chances of heart disease based on patient data using Logistic Regression.

## Project Overview
1. **Exploratory Data Analysis** using pandas and matplotlib  
2. **Feature preprocessing** and train-test split (80/20)  
3. **Model training** using Logistic Regression (scikit-learn)  
4. **Model evaluation** with accuracy metrics  
5. **Model serialization** using pickle

## Dataset
- **Source:** Kaggle Heart Disease Dataset
- **Rows:** 1025 samples  
- **Columns:** 14 (age, sex, cholesterol, etc.)  
- **Target:** `target` (1 = heart disease, 0 = no heart disease)

RangeIndex: 1025 entries, 0 to 1024
Data columns (total 14 columns):
 #   Column    Non-Null Count  Dtype  
---  ------    --------------  -----  
 0   age       1025 non-null   int64  
 1   sex       1025 non-null   int64  
 2   cp        1025 non-null   int64  
 3   trestbps  1025 non-null   int64  
 4   chol      1025 non-null   int64  
 5   fbs       1025 non-null   int64  
 6   restecg   1025 non-null   int64  
 7   thalach   1025 non-null   int64  
 8   exang     1025 non-null   int64  
 9   oldpeak   1025 non-null   float64
 10  slope     1025 non-null   int64  
 11  ca        1025 non-null   int64  
 12  thal      1025 non-null   int64  
 13  target    1025 non-null   int64 

---

## ⚙️ Technologies Used
- Python 3.x  
- Pandas  
- Scikit-learn  
- Matplotlib  

---
Results

Model used: Logistic Regression

Accuracy on test set: ≈ 79.51%

