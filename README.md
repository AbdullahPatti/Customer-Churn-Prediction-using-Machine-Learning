This project uses machine learning to predict whether a customer will **churn** (leave the service) or **stay**, based on their account, service, and usage data.

## 📂 Dataset
- **Telco Customer Churn Dataset** from [Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- Contains customer data like:
  - Contract type
  - Monthly charges
  - Internet service usage
  - Tenure
  - Support services
  - Payment method
  - And more

## 🎯 Objective
Build a classification model that predicts customer churn (Yes/No) and provides insights into which features influence churn.

## 🛠️ Tools Used
- **Python**
- **Pandas** — data cleaning and processing
- **NumPy** — numerical operations
- **Matplotlib** — data visualization
- **Scikit-learn** — machine learning models and evaluation

## 📊 Steps Followed
1. **Data Cleaning**
   - Handled missing values
   - Converted categorical variables into numeric format

2. **Exploratory Data Analysis (EDA)**
   - Visualized churn rates across various features
   - Checked feature correlation

3. **Feature Selection**
   - Removed irrelevant columns (like customerID)
   - Selected meaningful input variables for modeling

4. **Model Training**
   - Trained a classification model using:
     - Logistic Regression
     - Random Forest (best performance)

5. **Model Evaluation**
   - Accuracy: **79.31%**
   - Evaluated using:
     - Confusion Matrix
     - Classification Report (Precision, Recall, F1-Score)
     - ROC-AUC (optional)

6. **Insights**
   - Monthly contract customers churn more
   - Higher monthly charges are linked to churn
   - Longer-tenure customers are more likely to stay

## 📁 Files
- `Customer_Data.ipynb` — Jupyter notebook with full implementation
- `README.md` — This file

## ✅ Future Improvements
- Add more models for comparison (XGBoost, SVM)
- Build a simple web dashboard using Streamlit
- Improve feature engineering

## 📌 Author
Abdullah Haroon  
Connect with me on [LinkedIn](https://www.linkedin.com/)  
