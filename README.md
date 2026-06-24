# Customer Lifetime Value Prediction & Segmentation

Predicting customer lifetime value (CLV) is essential for understanding which customers contribute the most value and where businesses should focus their retention efforts. This project predicts 6-month customer lifetime value and segments customers into actionable groups to support marketing, retention, and revenue optimization decisions.

---

## Problem Statement

Businesses often spend the same amount of effort on all customers, even though not every customer contributes equally to revenue.

The objective of this project was to:

- Predict future customer lifetime value (CLV).
- Identify high-value and at-risk customers.
- Segment customers into actionable groups.
- Recommend strategies to improve retention and maximize revenue.

---

## Dataset

- **Customers:** 5,800+
- **Transactions:** 800,000+
- Historical purchase and behavioral data

### Features Used

- Recency
- Frequency
- Monetary Value
- Average Order Value
- Purchase History
- Customer Behavior Metrics

---

## Project Workflow

### 1. Data Cleaning & Preprocessing

- Removed missing values and duplicates.
- Handled outliers.
- Performed feature engineering.
- Prepared the dataset for modeling.

---

### 2. Exploratory Data Analysis

Analyzed:

- Purchase frequency distribution
- Revenue contribution patterns
- Customer spending behavior
- RFM characteristics

Key observation:

> A small percentage of customers contributed a disproportionately large share of revenue, indicating the need for differentiated retention strategies.

---

### 3. Customer Segmentation

Customers were segmented into groups based on their purchasing behavior:

### High Value Customers
- Frequent purchases
- High spending
- Strong retention potential

### Medium Value Customers
- Moderate purchase frequency
- Opportunity for upselling

### Low Value Customers
- Infrequent purchases
- High churn risk

### At-Risk Customers
- Previously active customers with declining engagement

---

## Model Development

Several regression models were evaluated for predicting 6-month Customer Lifetime Value.

Models explored:

- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor

Performance was compared using:

- MAE
- RMSE
- R² Score

The best-performing model was selected based on prediction accuracy and generalization capability.

---

## Key Insights

### 1. Revenue Concentration

The top customer segment generated a majority of overall revenue.

**Business implication:**
Protecting and retaining these customers should be a priority.

---

### 2. Churn Risk Segment

A group of customers showed declining activity despite previous purchases.

**Business implication:**
Targeted retention campaigns can prevent revenue loss.

---

### 3. Medium Value Customers

Many customers had growth potential.

**Business implication:**
Personalized recommendations and cross-selling can increase their lifetime value.

---

## Recommended Strategies

### High Value Customers

- Loyalty rewards
- Exclusive offers
- Premium experiences

### Medium Value Customers

- Product recommendations
- Bundling strategies
- Cross-selling campaigns

### At-Risk Customers

- Re-engagement emails
- Personalized discounts
- Win-back campaigns

### Low Value Customers

- Low-cost automated campaigns
- Behavioral nudges

---

## Business Impact

This framework can help businesses:

- Improve customer retention.
- Optimize marketing spend.
- Increase customer lifetime value.
- Identify high-value users.
- Prioritize customer acquisition efforts.
- Enable data-driven decision making.

---

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn
- Jupyter Notebook

---


## Future Improvements

- Deploy the model using Streamlit.
- Add XGBoost and LightGBM models.
- Incorporate customer demographics.
- Perform cohort analysis.
- Build a dashboard for business users.

---

## Conclusion

Customer Lifetime Value prediction enables businesses to move beyond one-size-fits-all marketing and focus resources where they generate the highest return. By combining predictive modeling with customer segmentation, this project provides a framework for improving retention, maximizing revenue, and supporting long-term business growth.

---
