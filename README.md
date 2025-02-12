

# **Diabetes Prediction Using Machine Learning**  
**Author:** Ndumbi Kimani  

## Project Overview
This project predicts **diabetes risk** using **machine learning models** and **exploratory data analysis (EDA)**. By analyzing key health indicators, it helps identify individuals at higher risk and enables early intervention.  

## Problem Statement
Diabetes is a growing global health concern. Early detection can improve treatment outcomes. This project uses **ML classification models** to predict diabetes based on patient health data.  

## Data & EDA Insights 
- **Key Features:** Glucose Level, BMI, Age, Blood Pressure, Insulin Levels  
- **Key Insights:**  
  - Higher glucose levels & BMI increase diabetes risk.  
  - Older individuals and those with high blood pressure are more likely to develop diabetes.  

## Machine Learning Approach
✅ **Models Used:**  
- Logistic Regression (Best Performance)  
- XGBoost (High Accuracy)  
- Random Forest, SVM, Decision Tree, KNN, Naive Bayes, SGDClassifier  

✅ **Feature Engineering:**  
- Data scaling using **MinMaxScaler**  
- Train-Test split for evaluation  

✅ **Performance Metrics:**  
- **Accuracy, Precision, Recall, F1-score, ROC-AUC**  

## Results & Recommendations 
- **Best Model:** **Logistic Regression** (Balanced precision & recall)  
- **XGBoost & Random Forest** performed well with hyperparameter tuning.  
- **Early screening based on model predictions** can reduce diabetes-related complications.  

## Tech Stack  
- **Python, Pandas, NumPy, Matplotlib, Seaborn**  
- **Scikit-Learn, XGBoost**  
- **Jupyter Notebook**  

## How to Run the Project 
1. Clone this repository:  
   ```bash
   git clone https://github.com/yourusername/Diabetes-Prediction.git
   cd Diabetes-Prediction
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook:  
   ```bash
   jupyter notebook
   ```
4. Explore the **EDA, ML models, and insights**.  

---
