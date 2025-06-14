# 🍷 Wine Quality Prediction using Random Forest Classifier

This project focuses on building a machine learning model to **predict the quality of wine** based on physicochemical tests using the **Random Forest Classifier**.

---

## 🎯 Objective

To develop a classification model that can accurately predict **wine quality scores** (on a scale of 0–10), based on features such as acidity, sugar content, pH, and alcohol percentage.

---

## 📊 Dataset

- **Name**: Wine Quality Dataset    
- **Types**: Red and White wine samples  
- **Samples**: ~1,599  
- **Features**:
  - Fixed acidity
  - Volatile acidity
  - Citric acid
  - Residual sugar
  - Chlorides
  - Free sulfur dioxide
  - Total sulfur dioxide
  - Density
  - pH
  - Sulphates
  - Alcohol  
- **Target**: Quality (Score from 0 to 10)

---

## 🧠 Model

We use **Random Forest Classifier**, a powerful ensemble learning method that combines multiple decision trees to improve accuracy and prevent overfitting.

```python
from sklearn.ensemble import RandomForestClassifier

# Load and initialize the model
model = RandomForestClassifier()
