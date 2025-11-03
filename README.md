# 🚀 Data-Driven Evaluation of Candidate Pipeline Performance

This repository contains the complete analytical pipeline, code, and synthesized data used to evaluate the effectiveness and impact of The Pipeline Fund's candidate training programs and partner organizations. This project was developed as a comprehensive portfolio piece demonstrating proficiency in Python, Pandas, and data visualization for strategic, mission-driven analysis.

## 🎯 Project Goal

The primary objective was to move beyond descriptive statistics to **quantify program impact** and identify **actionable equity gaps** across the candidate pipeline, partner performance, and electoral outcomes.

## 💾 Data Architecture

The analysis is based on six interconnected, synthesized CSV files that model a real-world pipeline system. These files were generated to test relational database skills and analytical capability across key organizational entities:

| Data File | Purpose |
| :--- | :--- |
| `candidates.csv` | **Core Entity:** Demographics, training status, and overall election status per candidate. |
| `campaigns.csv` | **Outcome Data:** Records specific electoral results (votes, win/loss) for each campaign run. |
| `participation.csv` | **Metrics Link:** Tracks program enrollment, completion status, scores, and satisfaction. |
| `programs.csv` | Details on training programs offered (type, activity status). |
| `partners.csv` | Organizational details for partner organizations (used for accountability). |
| `state_metrics.csv` | Pre-aggregated geographic benchmarks. |

## 🛠️ Methodology and Toolkit

The entire project pipeline was built for accuracy and efficiency, relying on high-standard data processing techniques.

* **Core Languages/Tools:** Python, Pandas, Matplotlib, Jupyter Notebooks
* **Key Techniques:** Complex multi-table merging (`left`/`inner` joins), calculating weighted averages, and deriving accurate metrics (e.g., Gold Standard Candidate Win Rate).
* **Data Integrity:** Implemented checks for missing data, strategic data imputation, and the conversion of boolean flags for accurate rate calculations.

## 📈 Key Project Findings

The analysis was segmented into three core areas, yielding the following strategic results:

### 1. Training Impact (The Value Proposition)

| Metric | Result | Strategic Insight |
| :--- | :--- | :--- |
| **Win Rate Lift** | **12.8%** (Trained 33.6% vs. Untrained 20.8%) | **Training is a high-value intervention.** This provides a quantifiable metric for fundraising and program advocacy. |
| **Program Volume** Training value is gained primarily by **participating at all**, not by increasing the number of programs taken. 

### 2. Program Effectiveness & Equity

* **Equity:** Program completion is **highly equitable** across all race and gender groups (all deltas $\le \pm 1.1\%$).
* **Scores:** Significant variance in final assessment scores was found, with **Black** candidates having the lowest average score, signaling a need for targeted post-training support.

### 3. Partner Accountability

* **Highest Performers:** Identified top partner organizations achieving the highest **Candidate Win Rate** (e.g., IL Civic Voices: 55.6%).
* **Diversity:** Several partners successfully recruited candidates from the **maximum 6 unique race/ethnicity groups**, proving broad commitment to inclusive recruitment.
* **Geographic Focus:** **Texas, Florida, and Georgia** are the top three states by total campaign wins.

## 🖥️ Presentation & Full Report

For a complete overview of the findings, data visualizations, and strategic recommendations, please view the final presentation:

Link to Google Slides Presentation --> https://docs.google.com/presentation/d/11jrT0B3LYvQpdQCHdsbzYe_Ey_eILXJsEI_X7yxZkro/edit?usp=sharing
