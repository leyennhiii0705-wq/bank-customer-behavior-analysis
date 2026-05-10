# Bank Customer Behavior Analysis Using Python

## Project Overview
This project applies Python and machine learning techniques to analyze banking customer behavior and predict whether customers will subscribe to term deposits after direct marketing campaigns.

The analysis focuses on identifying customer characteristics and behavioral patterns that influence deposit subscription decisions, while also evaluating the performance of classification models on highly imbalanced banking data.

---

## Objectives
- Analyze customer behavior using banking marketing data
- Perform end-to-end data analysis workflow
- Build predictive machine learning models for term deposit subscription
- Identify key business insights for banking marketing strategies
- Evaluate model performance on imbalanced datasets

---

## Dataset
- Dataset: BankCustomerData
- Domain: Banking Marketing Analytics
- Target Variable: `term_deposit`
- Problem Type: Binary Classification

---

## Technologies & Tools
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab

---

## Workflow
1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Data Visualization
5. Clustering Analysis
6. Machine Learning Modeling
7. Model Evaluation
8. Business Insight Reporting

---

## Machine Learning Models
### Logistic Regression
- AUC Score: 0.83
- F1-score: 0.31

### Random Forest
- AUC Score: 0.90
- F1-score: 0.31

Random Forest achieved the best overall performance in predicting customer subscription behavior.

---

## Key Insights
- Customers without housing loans were more likely to subscribe to term deposits
- Customers with higher account balances showed stronger subscription tendencies
- Occupation groups such as students and retirees had higher conversion rates
- Longer call durations were positively associated with successful subscriptions

---

## Challenges
The dataset was highly imbalanced, with only 5.41% positive subscription cases, making minority-class prediction difficult despite high overall accuracy.

---

## Optimization Recommendations
- Remove the `duration` variable to avoid data leakage
- Apply balancing techniques such as ADASYN
- Optimize Random Forest hyperparameters
- Experiment with XGBoost and LightGBM
- Integrate external banking and economic factors for better generalization

---

## Future Improvements
- Deploy an interactive dashboard for customer segmentation
- Apply real-time customer prediction pipelines
- Improve explainability using SHAP or feature importance analysis
- Integrate SQL-based data pipelines for scalable analytics

---

## Author
Nguyen Le Yen Nhi  
Financial Technology Student | Aspiring Data Analyst
