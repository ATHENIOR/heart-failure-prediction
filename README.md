# ❤️ Heart Failure Prediction using Machine Learning

> AI/ML project for predicting heart disease risk using clinical data and machine learning models.

---

## 📌 Overview

Cardiovascular diseases (CVDs) are the leading cause of death worldwide, accounting for nearly **17.9 million deaths annually**. Early prediction of heart failure can significantly improve patient outcomes and reduce mortality.

This project presents a **machine learning-based classification system** that predicts the likelihood of heart disease using clinical features.

📊 Dataset: Kaggle Heart Failure Prediction Dataset  
📈 Records: 918 patients  
🧠 Task: Binary Classification (Heart Disease / No Disease)

---

## 🎯 Objectives

- Develop a predictive model for heart failure detection  
- Compare Logistic Regression and Random Forest  
- Evaluate using multiple metrics (Accuracy, F1, ROC-AUC)  
- Provide interpretable insights using visualizations  

---

## 🧠 Models Used

### 🔹 Logistic Regression
- Linear classification model  
- Provides interpretable coefficients  
- Serves as baseline  

### 🔹 Random Forest Classifier
- Ensemble learning model  
- Handles non-linear relationships  
- More robust and accurate  

---

## ⚙️ Methodology

### 1. Data Preprocessing
- Replaced invalid zero values in features like cholesterol  
- One-hot encoding for categorical variables  
- Feature scaling using StandardScaler  

### 2. Exploratory Data Analysis (EDA)
- Correlation heatmap  
- Feature distribution analysis  

### 3. Train-Test Split
- 80% training, 20% testing  
- Stratified sampling  

### 4. Model Training
- Logistic Regression  
- Random Forest  

### 5. Evaluation Metrics
- Accuracy  
- Precision  
- Recall (Sensitivity)  
- F1 Score  
- ROC-AUC Curve  

---

## 📊 Results

| Model                | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|---------------------|---------|----------|--------|---------|--------|
| Logistic Regression | 85.87%  | 0.865    | 0.872  | 0.848   | 0.9156 |
| Random Forest       | 88.04%  | 0.889    | 0.891  | 0.882   | 0.9508 |

---

## 🔥 Key Insights

- Random Forest outperformed Logistic Regression  
- Captures complex non-linear relationships  
- Lower false negatives (important in medical diagnosis)  
- Strong ROC-AUC indicates excellent model performance  

---

## 📈 Visualizations

- Correlation Heatmap  
- Confusion Matrix  
- ROC Curve  

---

## 🧪 How to Run

### ▶️ Option 1: Google Colab

1. Upload the notebook  
2. Mount Google Drive  
3. Run all cells  

---

### ▶️ Option 2: Local (VS Code / Jupyter)

Install dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn
