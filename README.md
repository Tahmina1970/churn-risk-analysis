# Churn Risk Analysis & Customer Segmentation

## Overview

In this project, I analyzed customer churn behavior and built a risk segmentation model to identify customers likely to leave.

The goal was to simulate how a business analyst transforms raw data into **actionable insights and recommendations**.

---

## Objectives

* Identify customers at risk of churn
* Segment customers into High, Medium, and Low risk groups
* Build a behavior-based churn scoring model
* Generate business insights
* Automate outputs for reporting

---

## Dataset

The dataset used in this project is:

**Bank Customer Churn Dataset (Kaggle)**
It includes customer demographics, account activity, and financial behavior.

Key features:

* Customer age, gender, income
* Credit card usage and limits
* Transaction amount and frequency
* Months of inactivity
* Contact frequency

---

## Approach

### 1. Data Preparation

* Cleaned and standardized column names
* Handled missing values
* Explored customer behavior patterns

---

### 2. Risk Segmentation

Customers were classified into:

* **High Risk** – Likely to churn
* **Medium Risk** – Early warning signals
* **Low Risk** – Stable customers

---

### 3. Churn Score (Feature Engineering)

A churn score was calculated using:

* Months inactive
* Contact frequency
* Credit utilization
* Transaction behavior

---

### 4. Business Insights Generation

The analysis was translated into:

* Executive summary
* Business insights
* Recommended actions

---

### 5. Automation

The project generates:

* `churn_scored_customers.csv`
* `high_risk_customers.csv`
* `llm_prompt.txt`
* `ai_insights.txt`

---

## Key Results

* Total customers: 10,127
* High risk: 0.65%
* Medium risk: 34.39%
* Low risk: 64.96%

---

## Insights

* Customer inactivity is the strongest indicator of churn risk
* Medium-risk customers represent the largest opportunity segment
* Declining engagement signals early churn behavior

---

## Recommendations

* Launch re-engagement campaigns for medium-risk customers
* Offer retention incentives for high-risk customers
* Increase proactive customer communication

---

## Tools & Technologies

* Python (Pandas)
* Jupyter Notebook
* Feature Engineering
* Business Analysis

---

## Project Structure

```text
churn-risk-analysis/
│
├── churn_risk_analysis.ipynb
├── churn_scored_customers.csv
├── high_risk_customers.csv
├── llm_prompt.txt
├── ai_insights.txt
├── README.md
```

---

## How to Run

1. Open the notebook:

```bash
churn_risk_analysis.ipynb
```

2. Run all cells step by step

3. Outputs will be saved automatically

---

## Business Value

This project demonstrates how data can be used to:

* Identify at-risk customers
* Support retention strategies
* Provide actionable business insights

---

## About Me

I am a Data Analyst focused on customer analytics, churn prediction, and business-driven insights.

Location: Wuppertal, Germany
LinkedIn: (www.linkedin.com/in/tahmina-alam)

