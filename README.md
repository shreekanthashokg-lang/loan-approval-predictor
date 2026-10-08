# 🏦 CREADITSWISE LAON APPROVAL SYSTEM
**MINI PROJECT : PREDICTS LOAN APPROVAL**

---

## 📌PROJECT OVERVIEW
CreditWise is a **MACHINE LEARNING–BASED LOAN APPROVAL PREDICTION SYSTEM** DEPLOYED FOR  **SecureTrust Bank**.  
It addresses the challenges of **MANUAL LOAN VERIFICATION**, which is often prone to bias, inconsistency, and inefficiency.  
BY Leveraging Historical Loan Application Data and Predictive Modeling, the system automates decision-making to ensure **fair, accurate, and scalable loan approvals**.

### 💡 PROJECT BUSINESS IMPACT
- ✅ REDUCE **false rejections** → PREVENT LOSS OF CREDITWORTHY CUSTOMERS. 
- ✅ REDUCE **false approvals** → Minimize financial RISK EXPOSURE.  
- ✅ IMPROVE **operational efficiency** → FASTER LOAN PROCESSING, reduced manual workload.  
- ✅ ENHANCE**customer satisfaction** → Transparent and consistent approval process.  

---

## 📂 PROJECT FILES
- `docs/CreditWise Loan System.pdf` → DETAILED REQUIREMENTS, OBJECTIVES, AND PROBLEM STATEMENT.
- `data/loan_approval_data.csv` → Historical dataset containing applicant profiles and loan outcomes.  
- `notebooks/loan_approval_analysis.ipynb` → End-to-end ML pipeline implementation with exploratory analysis, model building, and evaluation.  

---

## 🎯 MACHINE LEARNING PIPELINE
1. **DATA EXPLORATION & CLEANING**  
   - Handle missing values, outliers, and categorical encoding.  
   - Normalize numerical features (income, loan amount).  

2. **FEATURE ENGINEERING**  
   - Derived features: Debt-to-Income ratio, Loan-to-Collateral ratio.  
   - One-hot encoding for categorical variables .  

3. **MODEL TRAINING**  
   - Algorithms tested: LOGISTIC REGRESSION, Random Forest, Gradient Boosting.  
   - Hyperparameter tuning with GridSearchCV.  

4. **MODEL EVALUATION & SELECTION**  
   - Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC.  
   - Focus on **Recall** TO MINIMIZE REJECTION OF GOOD CUSTOMERS.  

5. **RESULT ANALYSIS**  
   - FEATURE IMPORTANCE RANK.
   - Bias detection and fairness evaluation.  

---

## 📊 KEY RESULT
- **Best Model:** LOAN APPROVAL PREDICTOR : Random Forest Classifier
- **Accuracy:** 85%  
- **Recall:** 70% (critical for reducing false rejections)  
- **Precision:** 78% (balances risk of false approvals)  
- **KEY FEATURES DRIVING PREDICTIONS :**  
  - CREDICT SCORE
  - APPLICANT INCOME 
  - LOAN AMOUNT 
  - Collateral Availability  

---

## ⚙️ THE COMPLETE TECH STACK
- **Languages:** Python  
- **Libraries:** NumPy, Pandas, Scikit-learn, Matplotlib, Seaborn  
- **ENVIRONMENT :** Jupyter Notebook  
- **Version Control:** GitHub  
- **Data Handling:** CSV DATASET PREPROCESSING WITH PANDAS
- **Visualization:** Feature distributions, correlation heatmap AND  ROC CURVES  

---

## 🚀 GETTING STARTED WITH THE COMPLETE REPO
1. CLONE THIS REPOSITORY Clone REPOSITORY :  
   ```bash
