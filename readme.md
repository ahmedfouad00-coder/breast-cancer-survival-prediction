# 🧪 Breast Cancer Survival Prediction

This project focuses on predicting **patient survival** (Alive vs Dead) after being diagnosed with breast cancer, based on medical and clinical features.  
The goal is to support healthcare decisions by identifying high-risk patients who may require more aggressive treatment or closer monitoring.

---

## 📂 Project Workflow
- **Exploratory Data Analysis (EDA):**  
  Understanding the dataset, analyzing feature distributions, correlations, and survival outcomes.  

- **Data Preprocessing:**  
  - Removing noise and dropping irrelevant samples  
  - Feature scaling/normalization  
  - Encoding categorical variables (if present)  

- **Model Training:**  
  Multiple machine learning models were trained and compared:  
  - Voting Classifier  
  - Random Forest  
  - XGBoost  

- **Evaluation Metrics:**  
  Since survival prediction is a **binary classification problem**, models were evaluated using:  
  - Precision  
  - Recall  
  - F1-Score  
  - AUC Score  

---

## 📊 Results

| Model             | Precision | Recall | F1-Score | AUC  |
|-------------------|-----------|--------|----------|------|
| Voting Classifier | 0.55      | 0.74   | 0.63     | 0.90 |
| Random Forest     | 0.57      | 0.72   | 0.63     | 0.89 |
| XGBoost           | 0.47      | 0.78   | 0.59     | 0.90 |

✅ The **Voting Classifier** achieved the best balance between Recall, Precision, and F1-Score with a strong AUC score.  

---

## 🛠️ Tools & Libraries
- Python 3.x  
- Scikit-learn  
- XGBoost  
- Pandas, Numpy  
- Matplotlib, Seaborn  

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/ahmedfouad00-coder/breast-cancer-survival-prediction.git
   cd breast-cancer-survival-prediction
