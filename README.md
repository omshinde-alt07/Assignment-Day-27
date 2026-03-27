# Assignment 27

# ZeptoFresh — 15-Minute Delivery: EDA Case Study



---

## About This Repository

This repository contains my written answers for the **ZeptoFresh Case Study** assignment. The case study is based on Exploratory Data Analysis (EDA) of 110,000 order records from ZeptoFresh, a 15-minute food and essentials delivery company operating across 25 Indian cities in Q2 2025.

---

## File

| File | Description |
|---|---|
| `ZeptoFresh_Case_Study_Answers.pdf` | Complete written answers to all 6 questions |

---

## Questions Covered

| Question | Topic |
|---|---|
| (a) | Data Quality Diagnosis — identifying and treating 4 data issues |
| (b) | Distribution Analysis — skewness, histogram, log transformation |
| (c) | Correlation Interpretation — delivery time vs refunds, confounders |
| (d) | Bimodal Pattern — operational reasons and modeling implications |
| (e) | Business Trade-off — Precision vs Recall for late delivery prediction |
| (f) | Feature Engineering — 3 new features from existing columns |

---

## Key Takeaways

- `delivery_time_mins` is right-skewed — log transformation recommended before modeling
- Mumbai and Bangalore show a bimodal distribution indicating two fulfillment sub-populations
- The delivery–refund correlation (r = +0.74) is associative, not causal — `rain_flag` and `order_category` are likely confounders
- **Recall** should be prioritized over Precision given churn cost > reallocation cost
- F2-score is the recommended evaluation metric for the late delivery prediction model

---

## Assignment Details

| Detail | Info |
|---|---|
| Program | PG Diploma · AI-ML & Agentic AI Engineering |
| Institute | IIT Gandhinagar |
| Duration | 60–75 minutes |
| Submission | LMS + GitHub Repository Link |

---
