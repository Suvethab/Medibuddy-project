# MediBuddy Insurance Cost Prediction – Capstone Project

## 📌 Project Overview
This project analyzes health and demographic factors that influence insurance claim amounts and builds a machine learning model to predict insurance costs. The study is based on real-world healthcare insurance data inspired by MediBuddy’s digital health platform.

---

## 🎯 Objectives
- Perform Exploratory Data Analysis (EDA) to understand key factors affecting insurance claims
- Answer business-driven analytical questions related to risk assessment
- Build and evaluate a machine learning model to predict insurance charges
- Provide actionable insights for insurance policy design

---

## 📂 Dataset Description
Two datasets were used in this project:

1. **Insurance Price Data**
   - Age
   - Gender
   - BMI (Body Mass Index)
   - Insurance charges (target variable)

2. **Personal Details Data**
   - Number of dependents (children)
   - Smoking status
   - Geographic region

Both datasets were merged using a common **Policy Number**.

---

## 🛠️ Technologies & Tools Used
- Python
- Jupyter Notebook / Google Colab
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn

---

## 📊 Exploratory Data Analysis (EDA)
The following key business questions were analyzed:
1. Impact of gender on insurance claims  
2. Average insurance cost per policy  
3. Influence of geographic region on policy pricing  
4. Effect of number of dependents on claim amount  
5. Relationship between BMI and insurance charges  
6. Impact of smoking status on insurance cost  
7. Effect of age on insurance claims  
8. Feasibility of offering BMI-based discounts  

### 🔍 Key Insights
- Smoking status has the strongest impact on insurance charges
- Higher BMI and increasing age lead to higher claim amounts
- Dependents and geographic region also influence insurance costs
- Healthy BMI individuals may be eligible for premium discounts

---

## 🤖 Machine Learning Model
- **Model Used:** Random Forest Regressor
- **Target Variable:** Insurance Charges
- **Evaluation Metrics:**
  - R² Score
  - RMSE (Root Mean Squared Error)

### 📈 Model Performance
- R² Score: ~0.85  
- The model effectively captures non-linear relationships and feature interactions

---

## 🧠 Conclusion
The project demonstrates how data-driven analysis and machine learning can support better insurance risk assessment and premium pricing. Random Forest proved to be the most suitable model due to its strong predictive performance.

---

## ▶️ How to Run the Project
1. Clone the repository
2. Install dependencies:
