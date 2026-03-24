# 🏥 Hospital Readmission Prediction

## 📌 What This Project Is About
This project predicts whether a diabetic patient will be 
readmitted to hospital within 30 days of discharge using 
machine learning.

## 📊 Dataset
- Source: UCI Machine Learning Repository
- Records: 101,766 patients
- Features: 50 columns

## 🛠️ Tools Used
- Python
- Google Colab
- Pandas, Matplotlib, Seaborn
- Scikit-learn (Random Forest, Logistic Regression)

## 📈 Results
- Random Forest AUC Score: 0.78
- Logistic Regression AUC Score: 0.71
- Random Forest performed better overall

## 🔍 Key Observations
1. Older patients had higher readmission rates
2. More medications = higher risk
3. Longer hospital stays linked to readmission
4. Dataset was imbalanced — most patients not readmitted
5. Number of diagnoses was a strong predictor

## ✅ Conclusion
Random Forest was the best model for this project.
Future work includes trying XGBoost and building a 
Streamlit web app for doctors to use.
