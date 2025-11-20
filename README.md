##                                                         Telecom Customer Churn Prediction
<img width="1200" height="338" alt="image" src="https://github.com/user-attachments/assets/ab80875b-b03c-4284-833a-058c253b2c02" />

## What is Customer Churn?
Customer churn is defined as when customers or subscribers discontinue doing business with a firm or service.

Customers in the telecom industry can choose from a variety of service providers and actively switch from one to the next. The telecommunications business has an annual churn rate of 15-25 percent in this highly competitive market.

Individualized customer retention is tough because most firms have a large number of customers and can't afford to devote much time to each of them. The costs would be too great, outweighing the additional revenue. However, if a corporation could forecast which customers are likely to leave ahead of time, it could focus customer retention efforts only on these "high risk" clients. The ultimate goal is to expand its coverage area and retrieve more customers loyalty. The core to succeed in this market lies in the customer itself.

Customer churn is a critical metric because it is much less expensive to retain existing customers than it is to acquire new customers.

To detect early signs of potential churn, one must first develop a holistic view of the customers and their interactions across numerous channels.As a result, by addressing churn, these businesses may not only preserve their market position, but also grow and thrive. More customers they have in their network, the lower the cost of initiation and the larger the profit. As a result, the company's key focus for success is reducing client attrition and implementing effective retention strategy.
## 📊 Project Overview
Comprehensive end-to-end machine learning project analyzing customer churn in the telecommunications industry. Implements advanced feature engineering, handles class imbalance with SMOTE, and compares multiple ML algorithms with hyperparameter tuning.

## 🎯 Business Problem
Customer churn costs telecom companies billions annually. This project identifies at-risk customers and key churn drivers to enable proactive retention strategies.

## 📁 Dataset
- **Source**: Kaggle Telco Customer Churn Dataset
- **Size**: 7,043 customers, 21 features
- **Target**: Binary classification (Churn: Yes/No)
- The data set includes information about:
Customers who left within the last month – the column is called Churn
Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
Demographic info about customers – gender, age range, and if they have partners and dependents


## 🛠️ Technologies Used
- Python 3.2
- Pandas, NumPy
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Matplotlib, Seaborn

 ## Few glimpses of EDA:
1.Churn Destribution
<img width="1256" height="490" alt="image" src="https://github.com/user-attachments/assets/aaa007d2-6242-4f87-889f-9579dee91526" />
26.5 % of customers switched to another firm.

2. Churn vs categorical features
   <img width="1989" height="989" alt="image" src="https://github.com/user-attachments/assets/65f777b5-0f36-448d-8612-f64ce75ad546" />


  

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
