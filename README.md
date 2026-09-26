# 🏦 CREADITSWISE LAON APPROVAL SYSTEM
**MINI PROJECT : PREDICTS LOAN APPROVAL**

---

## 📌PROJECT OVERVIEW
CreditWise is a **MACHINE LEARNING–BASED LOAN APPROVAL PREDICTION SYSTEM** DEPLOYED FOR  **SecureTrust Bank**.  
It addresses the challenges of **MANUAL LOAN VERIFICATION**, which is often prone to bias, inconsistency, and inefficiency.  
By leveraging historical loan application data and Predictive Modeling, the system automates decision-making to ensure **fair, accurate, and scalable loan approvals**.

### 💡 BUSINESS IMPACT
- ✅ Reduce **false rejections** → Prevent loss of creditworthy customers.  
- ✅ Reduce **false approvals** → Minimize financial RISK EXPOSURE.  
- ✅ Improve **operational efficiency** → Faster loan processing, reduced manual workload.  
- ✅ Enhance **customer satisfaction** → Transparent and consistent approval process.  

---

## 📂 PROJECT FILES
- `docs/CreditWise Loan System.pdf` → Detailed requirements, objectives, and problem statement.  
- `data/loan_approval_data.csv` → Historical dataset containing applicant profiles and loan outcomes.  
- `notebooks/loan_approval_analysis.ipynb` → End-to-end ML pipeline implementation with exploratory analysis, model building, and evaluation.  

---

## 🎯 ML PIPELINE
1. **DATA EXPLORATION & CLEANING**  
   - Handle missing values, outliers, and categorical encoding.  
   - Normalize numerical features (income, loan amount).  

2. **Feature Engineering**  
   - Derived features: Debt-to-Income ratio, Loan-to-Collateral ratio.  
   - One-hot encoding for categorical variables (employment type, collateral availability).  

3. **MODEL TRAINING**  
   - Algorithms tested: Logistic Regression, Random Forest, Gradient Boosting.  
   - Hyperparameter tuning with GridSearchCV.  

4. **MODEL EVALUATION & SELECTION**  
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
- **KEY FEATURES DRIVING PREDICTIONS :**  
  - Credit Score  
  - Applicant Income  
  - LOAN AMOUNT 
  - Collateral Availability  

---

## ⚙️ TECH STACK
- **Languages:** Python  
- **Libraries:** NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn  
- **ENVIRONMENT :** Jupyter Notebook  
- **Version Control:** GitHub  
- **Data Handling:** CSV dataset preprocessing with Pandas  
- **Visualization:** Feature distributions, correlation heatmaps, ROC curves  

---

## 🚀 GETTING STARTED
1. CLONE THIS REPOSITORY Clone REPOSITORY :  
   ```bash
   git clone <repo-link>
