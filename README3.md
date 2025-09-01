# 🌲 Covertype Multi-Class Classification

## 📌 Project Overview
This project applies **machine learning techniques** on the **Covertype dataset** to predict the type of forest cover.  
The workflow includes **data preprocessing, dimensionality reduction with PCA, and multi-class classification models**.

---

## 🔑 Key Steps
1. **Data Cleaning**  
   - Handling missing values.  
   - Detecting and treating outliers.  

2. **Exploratory Data Analysis (EDA)**  
   - Distribution of features.  
   - Correlation heatmaps.  
   - Class balance check.  

3. **Dimensionality Reduction**  
   - Applied **Principal Component Analysis (PCA)** to visualize and reduce dimensionality.  

4. **Modeling**  
   - Implemented and compared multiple classifiers:  
     - Logistic Regression  
     - Decision Tree  
     - Random Forest  
     - XGBoost  

5. **Evaluation**  
   - Used metrics: **Accuracy, Precision, Recall, F1-score**.  
   - Visualization of confusion matrices for model comparison.  

---

## 📊 Results
- PCA visualization showed class overlap but some separability.  
- Best performing model: **XGBoost** with the highest accuracy and balanced precision/recall.  

---

## ⚙️ Tech Stack
- Python 🐍  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- XGBoost  

---

## 🚀 How to Run
```bash
git clone <repo-link>
cd covertype-classification
jupyter notebook task3.ipynb
