# 💓 Heart Disease Prediction using Naive Bayes

This project implements a heart disease prediction model using the **Naive Bayes classification algorithm**. It uses patient medical data to classify whether the person has a heart disease or not.

---

## 📁 Dataset

The dataset contains the following features:

- Age, Sex, Chest Pain Type  
- Resting Blood Pressure, Cholesterol  
- Fasting Blood Sugar, Max Heart Rate  
- ST Slope, Exercise Induced Angina, Oldpeak  
- Target variable: **HeartDisease** (0 = No, 1 = Yes)

---

## ⚙️ Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📊 Model Evaluation Metrics

| Metric            | Value   |
|-------------------|---------|
| Accuracy Score     | 0.8540  |
| Precision          | 0.8380  |
| Recall             | 0.8730  |
| F1 Score           | 0.8554  |

---

## 📑 Classification Report

| Class | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|----------|---------|
| 0     | 0.87      | 0.80   | 0.83     | 250     |
| 1     | 0.84      | 0.88   | 0.86     | 250     |
| **Accuracy**   |           |        | 0.85     | 500     |
| **Macro avg**  | 0.86      | 0.84   | 0.84     | 500     |
| **Weighted avg** | 0.86    | 0.85   | 0.85     | 500     |

---

## 📈 Visualizations

- Correlation heatmap  
- Distribution plots by age, chest pain, cholesterol, max heart rate  
- Confusion matrix  
- Pie chart showing class distribution  
- Pairplot of selected features  

---

## ✅ Sample Prediction

Example input:
```python
[29, 0, 2, 100, 106, 1, 2, 80, 1, 1, 1]
