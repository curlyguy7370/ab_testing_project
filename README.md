# ab_testing_project
A/B testing analysis on e-commerce KPIs with Python, Excel &amp; Tableau — real B2B marketing project.


## A/B Testing on Marketing Performance KPIs

This repository showcases an A/B testing project I conducted during an internship at a B2B digital-marketing company that supports retailers in optimizing their online performance.

The goal of the analysis was to evaluate key performance indicators, such as Conversion Rate.

# 🧪 A/B Testing of E-commerce KPIs

## 📋 Project Overview
This project analyzes the results of **A/B testing experiments** to evaluate key **e-commerce KPIs** such as **Conversion Rate**, **ROAS (Return on Advertising Spend)**, **Return Rate**, **Orders from Repeat Customers**, and **Margin**.

It was carried out as part of my work for a **B2B company** in the **e-commerce industry**, which supports retailers in managing their **online stores** and **marketing channels**.  
The objective was to assess the effectiveness of marketing and design interventions through data-driven testing and provide **actionable insights** to improve business performance.

---

## ⚙️ Methodology
1. **Data Preparation**  
   - Imported and merged performance datasets exported from the Shopify accounts of multiple clients.  
   - Cleaned and standardized the data using **Python (Pandas, NumPy)** to ensure comparability between **control** and **test** groups.  
   - Normalized metrics and structured them for hypothesis testing.

2. **A/B Testing & Statistical Analysis**  
   - Performed **hypothesis testing** to check whether observed KPI differences were statistically significant.  
   - Used **t-tests** for comparing continuous KPIs (e.g., conversion rate, ROAS, margin).  
   - Analyzed **p-values** to confirm or reject null hypotheses (significance threshold: α = 0.05).  
   - Summarized results in structured outputs highlighting which metrics significantly improved in the test variant.

3. **Visualization**  
   - Built **interactive Tableau dashboards** to explore performance differences between test and control groups.  
   - Visualized KPI trends, significance levels, and client-specific outcomes for improved interpretation.

---

## 💾 Data Sources
The dataset used in this project is provided as:

**`ab_test.csv`**

It was derived from **Shopify reports** exported from client accounts managed by the company.  
The data represents aggregated performance results before and after specific interventions, anonymized for confidentiality.  
This dataset forms the analytical foundation of the **A/B testing** conducted in the accompanying Jupyter notebook.

---

## 📊 Visualizations
The analytical results were transformed into **interactive visual dashboards** using **Tableau** to enhance interpretability and storytelling.  
These dashboards provide a visual comparison between control and test groups across key KPIs, helping identify which marketing and design interventions had the strongest effects.

🔗 **View the dashboards here:**  
[Tableau Public — A/B Test KPI Dashboard](https://public.tableau.com/app/profile/riccardo.conti)

---

## 🧠 Interpretation and Key Findings
- The A/B test revealed **statistically significant improvements** in conversion rate and repeat purchase share for several client interventions.  
- Results for **ROAS** and **Margin** varied depending on campaign and audience, highlighting the importance of multi-metric evaluation.  
- The analysis emphasized that **continuous testing and iteration** are essential for maximizing ROI in e-commerce.  
- Findings were used to propose **strategic recommendations**, including:  
  - Reallocating marketing budgets toward top-performing channels.  
  - Refining campaign timing and creative assets.  
  - Integrating A/B testing insights into ongoing optimization cycles.

---

