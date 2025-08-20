# Predicting-Loan-Approval-using-Logistic-Regression-and-Decision-Trees
This project builds ML models to predict loan/insurance approval, comparing Logistic Regression and Decision Tree Classifier. It applies regularization and hyperparameter tuning with GridSearchCV to optimize performance and evaluate model effectiveness.
# Loan/Insurance Approval Prediction 🔎

### Real-world Interpretation
Banks usually approve loans if:
- Income is high  
- Credit history is good  
- Loan amount is reasonable compared to income  
- Property is in a developed area  

This dataset simulates exactly that scenario.  

---

## 📌 Tasks to Perform

### 1. Data Preprocessing
- Handle missing values  
- Encode categorical features (e.g., Gender, Education)  
- Apply feature scaling (important for Logistic Regression)  
- Split dataset into training (70%) and testing (30%)  

### 2. Model Training (Without GridSearchCV)
- Logistic Regression with penalties: **L1, L2, ElasticNet**  
- Decision Tree with basic parameters: `max_depth`, `min_samples_split`  
- Evaluate models using **Accuracy, Precision, Recall, F1 Score**  

### 3. Model Training (With GridSearchCV)
- Logistic Regression hyperparameters: `C`, `penalty`, `solver`, `l1_ratio`  
- Decision Tree hyperparameters: `max_depth`, `min_samples_split`, `min_samples_leaf`, `criterion`  
- Use **GridSearchCV** for balanced splits  

### 4. Comparison & Analysis
- Compare Logistic Regression vs. Decision Tree performance  
- Show the effect of **regularization & tuning**  
- Discuss:  
  - Logistic Regression → interpretable, good for linear patterns  
  - Decision Tree → better for non-linear, rule-based explanations  

---

## 📂 Deliverables
- **Jupyter Notebook** including:  
  - Data preprocessing steps  
  - Model training & evaluation (before and after GridSearchCV)  
  - Performance metrics & visualizations (**confusion matrix, bar plots of scores**)  
