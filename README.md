# 📊 Customer Retention & Product Analytics Case Study

## 🔍 Project Overview

This project analyzes customer churn behavior to identify high-risk user segments, uncover retention drivers, and design data-driven experimentation strategies.

Instead of focusing purely on churn prediction, this study emphasizes:

- User segmentation  
- Lifecycle analysis  
- Feature impact evaluation  
- High-risk cohort identification  
- A/B test experiment design  
- Business-driven retention strategy  

The goal is to move from descriptive analysis to actionable product decision-making.

---

# 🎯 Business Objective

Customer churn rate: **26.58%**

The objective of this analysis is to:

- Identify segments driving disproportionate churn  
- Understand lifecycle friction points  
- Quantify retention-driving product features  
- Design and statistically evaluate an intervention strategy  

---

# 📁 Dataset

Telco Customer Churn dataset  
~7,000 customers  

Features include:

- Demographics (gender, senior citizen, dependents)  
- Subscription details (contract type, internet service)  
- Add-on services (OnlineSecurity, TechSupport, etc.)  
- Financials (MonthlyCharges, TotalCharges)  
- Target variable: **Churn (Yes/No)**  

---

# 📈 Key Findings

## 1️⃣ Lifecycle Risk Analysis

| Tenure | Churn Rate |
|--------|------------|
| 0–6 months | 53.3% |
| 6–12 months | 35.8% |
| 1–2 years | 28.7% |
| 2–4 years | 20.3% |
| 4–6 years | 9.5% |

**Insight:**  
Early lifecycle (first 6 months) is the highest churn risk stage. Onboarding and early engagement are critical retention levers.

---

## 2️⃣ Contract-Based Segmentation

| Contract Type | Churn Rate |
|---------------|------------|
| Month-to-month | 42.7% |
| One year | 11.2% |
| Two year | 2.8% |

**Insight:**  
Long-term contracts significantly reduce churn risk.

---

## 3️⃣ Feature Impact on Retention

Strong retention drivers identified:

- OnlineSecurity → 41.7% (No) vs 14.6% (Yes)  
- TechSupport → 41.6% (No) vs 15.1% (Yes)  
- OnlineBackup → 39.9% (No) vs 21.5% (Yes)  

**Insight:**  
Support-based add-ons dramatically improve customer stickiness.

---

# 🚨 High-Risk Segment Identification

A high-risk segment was defined as:

- Tenure ≤ 6 months  
- Month-to-month contract  
- Fiber optic internet  
- No OnlineSecurity  
- No TechSupport  

### Segment Impact:

- Represents **7.57% of total users**  
- Churn rate: **76.88%**  
- Contributes **21.88% of total churn**  

**Insight:**  
A small segment drives a disproportionate share of churn, making it a high-leverage intervention target.

---

# 🧪 A/B Experiment Design

## Hypothesis

Offering a free 3-month bundle of OnlineSecurity + TechSupport to high-risk users will reduce churn.

## Experiment Setup

- Control Group: No intervention  
- Treatment Group: Free support bundle  
- Primary Metric: Churn rate  
- Statistical Test: Two-proportion z-test  

## Results

- Z-statistic: -4.80  
- P-value: 0.00000156  

**Conclusion:**  
The intervention significantly reduces churn (p < 0.05).  
Treatment group churn rate is statistically lower than control group.  

This supports scaling the intervention strategy.

---

# 📊 Metrics Framework

Key product metrics defined:

- Overall churn rate  
- Churn by lifecycle stage  
- Churn by contract type  
- Feature adoption impact  
- High-risk segment contribution  
- Experiment uplift  

---

# 💡 Strategic Recommendations

1. Early Lifecycle Engagement  
   Introduce onboarding campaigns within first 90 days.

2. Contract Conversion Strategy  
   Incentivize month-to-month users to upgrade to annual contracts.

3. Feature Bundling  
   Offer security and support add-ons to high-risk users.

4. Targeted CRM Interventions  
   Focus retention efforts on high-risk cohorts contributing disproportionately to churn.

---

# 🛠 Tools & Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Statsmodels  
- Hypothesis Testing  
- Two-Proportion Z-Test  

---

# 🚀 Business Impact

By targeting only 7.5% of users:

- Potential to reduce ~22% of total churn  
- Enables high-ROI retention campaigns  
- Moves from reactive churn prediction to proactive lifecycle intervention  

---

# 📌 Key Takeaways

This project demonstrates:

- Segmentation framework design  
- Lifecycle-based retention analysis  
- Feature impact quantification  
- Experimentation mindset  
- Statistical validation of product interventions  
- Data-driven business decision support  
