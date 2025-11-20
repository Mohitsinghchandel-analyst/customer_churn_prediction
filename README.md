# customer_churn_prediction
###Telecom Customer Churn Prediction
## 📊 Project Overview
Comprehensive end-to-end machine learning project analyzing customer churn in the telecommunications industry. Implements advanced feature engineering, handles class imbalance with SMOTE, and compares multiple ML algorithms with hyperparameter tuning.

## 🎯 Business Problem
Customer churn costs telecom companies billions annually. This project identifies at-risk customers and key churn drivers to enable proactive retention strategies.

## 📁 Dataset
- **Source**: Kaggle Telco Customer Churn Dataset
- **Size**: 7,043 customers, 21 features
- **Target**: Binary classification (Churn: Yes/No)

## 🛠️ Technologies Used
- Python 3.2
- Pandas, NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Matplotlib, Seaborn
  

## 🔍 Key Features
- **Advanced Feature Engineering**: RFM analysis, tenure groups, interaction features
- **Imbalanced Data Handling**: SMOTE implementation
- **Multiple ML Models**: Logistic Regression, Decision Tree, Random Forest, Gradient Boosting
- **Hyperparameter Tuning**: GridSearchCV with 5-fold cross-validation
- **Comprehensive Evaluation**: Accuracy, Precision, Recall, F1-Score, ROC-AUC

## 📈 Results
- **Best Model**: Random Forest (Optimized)
- **ROC-AUC Score**: 0.85+ 
- **Recall**: 78%+ for churn class
- **Key Churn Drivers**: Contract type, tenure, monthly charges

## 💡 Business Insights
1. Month-to-month contracts show 3x higher churn risk
2. First-year customers require enhanced engagement
3. Service bundling reduces churn by 40%

## 🚀 How to Run
