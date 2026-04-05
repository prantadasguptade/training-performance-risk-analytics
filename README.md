# Training Performance & Risk Analytics Dashboard

## Overview

This project analyzes employee training data to evaluate completion trends, performance levels, and potential compliance risks.

It is designed to simulate how organizations can monitor learning effectiveness and identify areas requiring intervention using data-driven insights.

---
## Business Problem
Organizations invest heavily in employee training but lack visibility into:
- Which learners are at risk of failing
- What factors impact training performance
- How to improve training ROI

## Objective
Build a data-driven system to:
- Identify high-risk learners
- Analyze performance patterns
- Provide actionable business recommendations

---

## Solution

This dashboard provides a structured approach to:

* Track training completion against targets
* Identify low-performing courses and departments
* Detect high-risk employees
* Support decision-making through actionable insights

---

## Dashboard Structure

### 1. Executive Overview

* KPI tracking (Completion Rate, Target, Gap, Avg Days)
* Training completion trend
* Department-wise completion

### 2. Performance Insights

* Courses driving low performance
* Department-level analysis of low performers
* Behavior analysis (Score vs Completion Time)

### 3. Risk & Action Dashboard

* High-risk employee identification
* Risk distribution across departments
* Action table for immediate intervention

---

## Key Insights

* Completion rate is below the target benchmark (85%)
* Sales and HR departments show lower completion and higher risk levels
* Certain courses contribute significantly to low performance
* High-risk employees require immediate follow-up and monitoring

---

## Recommended Actions

* Prioritize high-risk employees for completion tracking
* Introduce department-level accountability mechanisms
* Review course effectiveness where low scores are concentrated

---

## Tools & Technologies

* Power BI
* DAX
* Excel (data simulation)

---

## Dataset

The dataset used in this project is simulated based on real-world Learning & Development scenarios observed in enterprise environments.
The dataset includes:
- Learner attendance
- Assessment scores
- Course completion status
- Submission timelines
---
## Approach

1. Data Cleaning & Preprocessing
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Risk Segmentation
---
## Risk Classification Approach

A rule-based approach is used to classify learner risk:

- Incomplete learners are marked as High Risk
- Learners with low scores (<70) are Medium Risk
- Learners with delayed completion (>10 days) are Medium Risk
- Others are classified as Low Risk

This model is simple, interpretable, and aligned with business needs.
---
## Dashboard Preview

### Executive Overview
![Executive Overview](assets/Page1.png)

### Performance Insights
![Performance Insights](assets/Page2.png)

### Risk & Action Dashboard
![Risk Dashboard](assets/Page3.png)

## Business Recommendations

- Implement early warning system for low attendance learners
- Send automated alerts for delayed submissions
- Focus additional support on high-risk coursesm

## Future Scope

- Deploy model using Streamlit dashboard
- Integrate with LMS platforms (e.g., Cornerstone, ServiceNow)
- Real-time risk monitoring system




## Note

This project is created for portfolio purposes and demonstrates applied business analytics and decision-support thinking.
