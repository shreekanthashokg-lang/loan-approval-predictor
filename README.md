# 🏦 CreditWise Loan Approval System
**MINI PROJECT : PREDICTS LOAN APPROVAL**

---

## 📌 Project Overview
CreditWise is a **MACHINE LEARNING–based loan approval prediction system** developed for **SecureTrust Bank**.  
It addresses the challenges of **manual loan verification**, which is often prone to bias, inconsistency, and inefficiency.  
By leveraging historical loan application data and predictive modeling, the system automates decision-making to ensure **fair, accurate, and scalable loan approvals**.

### 💡 Business Impact
- ✅ Reduce **false rejections** → Prevent loss of creditworthy customers.  
- ✅ Reduce **false approvals** → Minimize financial risk exposure.  
- ✅ Improve **operational efficiency** → Faster loan processing, reduced manual workload.  
- ✅ Enhance **customer satisfaction** → Transparent and consistent approval process.  

---

## 📂 PROJECT FILES
- `docs/CreditWise Loan System.pdf` → Detailed requirements, objectives, and problem statement.  
- `data/loan_approval_data.csv` → Historical dataset containing applicant profiles and loan outcomes.  
- `notebooks/loan_approval_analysis.ipynb` → End-to-end ML pipeline implementation with exploratory analysis, model building, and evaluation.  

---

## 🎯 ML PIPELINE
1. **Data Exploration & Cleaning**  
   - Handle missing values, outliers, and categorical encoding.  
   - Normalize numerical features (income, loan amount).  

2. **Feature Engineering**  
   - Derived features: Debt-to-Income ratio, Loan-to-Collateral ratio.  
   - One-hot encoding for categorical variables (employment type, collateral availability).  

3. **Model Training**  
   - Algorithms tested: Logistic Regression, Random Forest, Gradient Boosting.  
   - Hyperparameter tuning with GridSearchCV.  

4. **Model Evaluation & Selection**  
   - Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC.  
   - Focus on **Recall** to minimize rejection of good customers.  

5. **RESULT ANALYSIS**  
   - Feature importance ranking.  
   - Bias detection and fairness evaluation.  

---

## 📊 KEY RESULT
- **Best Model:** Loan-Approval-Predictor (Random Forest Classifier)  
- **Accuracy:** 85%  
- **Recall:** 70% (critical for reducing false rejections)  
- **Precision:** 78% (balances risk of false approvals)  
- **Key Features Driving Prediction:**  
  - Credit Score  
  - Applicant Income  
  - Loan Amount  
  - Collateral Availability  

---

## ⚙️ TECH STACK
- **Languages:** Python  
- **Libraries:** NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook  
- **Version Control:** GitHub  
- **Data Handling:** CSV dataset preprocessing with Pandas  
- **Visualization:** Feature distributions, correlation heatmaps, ROC curves  

---

## 🚀 GETTING STARTED
1. Clone this repository:  
   ```bash
   git clone <repo-link>
