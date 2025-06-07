#  Bank Marketing Predictive Analysis

##  Problem Statement

The Portuguese bank has experienced a decline in revenue due to fewer clients subscribing to **term deposit products** — an important source of stable revenue.

**Goal:**  
Build a predictive model to identify clients with a higher likelihood of subscribing to a term deposit, so the bank can better target its marketing efforts and optimize campaign ROI.

---

##  Dataset

- Source: [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/dataset/222/bank+marketing)
- Type: Classification
- Target variable: `y` (whether the client subscribed to a term deposit)
- Attributes:
  - Client attributes (age, job, marital status, education, etc.)
  - Campaign attributes (previous outcome, contact type, etc.)
  - Economic indicators (euribor3m, emp.var.rate, etc.)

---

##  Project Workflow

### 1️ Exploratory Data Analysis (EDA)
- Univariate & Bivariate analysis
- Outlier detection
- Handling missing values
- Feature engineering
- Business insights from data patterns

### 2️ Model Building
- Logistic Regression (baseline model)
- Decision Tree
- Random Forest
- XGBoost

### 3️ Hyperparameter Tuning
- GridSearchCV used to optimize Decision Tree, Random Forest, and XGBoost models.

### 4️ Evaluation Metrics
- Accuracy
- AUC Score
- ROC Curve
- Confusion Matrix

### 5️ Feature Selection
- Identified top contributing features influencing term deposit subscription.

---

##  Tools & Libraries Used

- Python
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- GridSearchCV (for hyperparameter tuning)

---

##  Results & Business Insights

- Best performing model: **XGBoost** with high AUC and accuracy.
- Key predictive features identified to guide future marketing strategies.
- Business insights generated from EDA to assist bank decision-makers.

---

##  Future Work

- Implement model explainability (SHAP, LIME).
- Deploy as a web app for marketing teams to use.
- Automate real-time predictions on new customer data.

---

##  Conclusion

By building accurate predictive models and extracting business insights, this project provides a valuable framework to help the Portuguese bank **target clients more effectively**, optimize marketing campaigns, and increase subscription rates for term deposits — ultimately improving overall revenue.

---

##  Contribution

This project was part of my **AI/ML learning journey** and showcases practical application of:
- EDA techniques
- Supervised learning models
- Hyperparameter tuning
- Business insights generation

---

