# Customer Churn Analysis & Risk Prediction

## 📌 Project Overview

An end-to-end customer churn analysis and risk prediction project built using Python, Machine Learning, and Power BI.

The project analyzes customer behavior, identifies key factors associated with churn, predicts customer churn probability, and segments customers into Low, Medium, and High Risk categories.

## 🎯 Business Objective

The objective of this project is to help businesses:

- Identify customers who are likely to churn
- Understand the major drivers of customer churn
- Segment customers based on churn risk
- Prioritize high-risk customers for retention strategies
- Monitor churn KPIs through an interactive Power BI dashboard

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Power BI
- DAX
- Data Visualization
- Machine Learning

## 🤖 Machine Learning Model

A classification model was developed to predict customer churn probability.

### Model Performance

| Metric | Score |
|---|---:|
| Accuracy | 75.5% |
| Precision | 52.6% |
| Recall | 77.8% |
| F1 Score | 62.8% |
| ROC-AUC | 84.1% |

The ROC-AUC score of **0.841** indicates good ability to distinguish between customers who churn and those who do not.

## 🔍 Key Churn Drivers

Feature importance analysis identified the following major factors:

- Customer tenure
- Contract type
- Monthly charges
- Internet service type
- Payment method
- Online security
- Technical support

Shorter tenure and month-to-month contracts were particularly associated with higher churn risk.

## ⚠️ Customer Risk Segmentation

Customers were segmented into three risk categories:

| Risk Category | Customers | Churn Rate |
|---|---:|---:|
| Low Risk | 619 | 5.33% |
| Medium Risk | 353 | 26.91% |
| High Risk | 437 | 56.29% |

The high-risk segment shows a substantially higher actual churn rate, making it the primary segment for retention efforts.

## 📊 Power BI Dashboard

The Power BI dashboard contains two main pages:

### Page 1 — Executive Churn Overview

Provides an overall view of customer churn, including key KPIs and churn patterns across customer characteristics.

### Page 2 — Customer Churn Risk Analysis

Provides:

- High-risk customer KPIs
- Churn rate by risk category
- Churn rate by contract type
- Churn rate by tenure segment
- Top high-risk customers by churn probability
- Customer-level churn risk details
- Interactive filtering using slicers

## 💡 Business Insights

- High-risk customers have a significantly higher actual churn rate than low-risk customers.
- Month-to-month contracts are an important churn indicator.
- Customers with shorter tenure require greater retention attention.
- Higher monthly charges are associated with increased churn risk.
- Customers without online security and technical support appear more vulnerable to churn.

## 📁 Project Files

- `Customer_Churn_Risk_Analysis.pbix` — Power BI dashboard
- Dashboard screenshots — Power BI report pages

## 👤 Author

**Jyoti Singh Jayant**
