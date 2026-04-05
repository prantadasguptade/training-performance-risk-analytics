# 📊 Training Performance & Risk Analytics

A Power BI risk analytics solution to identify high-risk learners in enterprise training programmes — built to support L&D decision-making at scale.

> *Originally developed at PwC to support Learning & Development team decisions across enterprise training programmes.*

---

## 🔴 Problem

Organisations invest heavily in employee training yet lack visibility into:
- Which learners are at risk of failing or dropping out
- What factors drive poor training performance
- How to intervene early enough to improve outcomes

---

## ✅ Solution

A **data-driven risk classification system** built in Power BI that:
- Analyses learner performance across attendance, scores, and completion time
- Classifies each learner into Low / Medium / High risk tiers
- Surfaces actionable insights for training managers via an interactive dashboard

---

## 💼 Business Impact

| Metric | Result |
|---|---|
| Learners monitored | 100 across multiple departments |
| High-risk learners identified | ~33% flagged for early intervention |
| Key risk drivers | Attendance rate, assessment score, completion delay |
| Decision support | Enabled proactive manager action before course end |

---

## 🧠 Risk Classification Logic

| Condition | Risk Level |
|---|---|
| Training status = Incomplete |  High Risk |
| Assessment score < 70 or  Completion delayed > 10 days |  Medium Risk |
| All conditions met |  Low Risk |

Rule-based approach chosen for **transparency and interpretability** — every classification traces back to a specific business rule.

---

## ⚙️ Approach

1. Data cleaning and preprocessing (Excel / CSV)
2. Exploratory Data Analysis
3. Feature engineering (risk score components)
4. Rule-based risk classification using DAX
5. Interactive dashboard in Power BI

---

## Dashboard Preview

### Executive Overview
![Executive Overview](assets/Page1.png)

### Performance Insights
![Performance Insights](assets/Page2.png)

### Risk & Action Dashboard
![Risk Dashboard](assets/Page3.png)

---

## 🚀 How to Open

1. Download `Training Performance & Risk Analytics Dashboard.pbix` from this repo
2. Open in **Power BI Desktop** (free — [download here](https://powerbi.microsoft.com/desktop/))
3. Navigate to the Risk Dashboard tab to explore learner risk classifications
4. A **PDF preview** is also available in this repo for those without Power BI

---

## 🛠️ Tech Stack

| Tool | Purpose |
|---|---|
| Power BI | Dashboard and visualisation |
| DAX | Risk scoring logic and calculated measures |
| Advanced Excel / CSV | Data preparation and cleaning |

---

## 🔮 Future Scope

- Integrate with LMS platforms (e.g., Cornerstone, ServiceNow CSOD)
- Automate risk alerts to managers via Power Automate
- Add predictive layer using Python (scikit-learn) for ML-based early warning
- Expand dataset to include learner engagement and time-on-task signals

---

## 📄 Note

Dataset is simulated for portfolio demonstration. No real employee or organisational data is included.

---

## 👤 Author

**Pranta Dasgupta** | Data Analyst | 5+ years at PwC & Tata AIG

🔗 [LinkedIn](https://www.linkedin.com/in/prantadasgupta/) | 📧 pranta.dasgupta.de@gmail.com
