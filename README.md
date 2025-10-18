# ab_testing_project
A/B testing analysis on e-commerce KPIs with Python, Excel &amp; Tableau — real B2B marketing project.

# 🧪 A/B Testing of E-commerce KPIs

## 📋 Project Overview
This project analyzes the results of **A/B testing experiments** to study **e-commerce KPIs** such as **Conversion Rate**.

It was carried out as part of my work for a **B2B company** in the **e-commerce industry**, which supports retailers in managing their **online stores** and **marketing channels**.  

The project was designed to perform a year-over-year (2025 vs 2024) performance comparison for each client, using A/B testing and visualization techniques to uncover temporal changes in clients' KPIs and provide **actionable insights** to improve business performance.

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

It was derived from Shopify reports exported from client accounts managed by the company.
The data is organized year over year, containing aggregated KPI values for each client across 2024 and 2025, allowing for temporal comparison of performance.
The dataset serves as the analytical foundation for the A/B testing and visualization conducted.
Client names, financial figures, and other sensitive information have been modified to ensure confidentiality.

---

## 📊 Visualizations
The analytical results were transformed into **interactive visual dashboards** using **Tableau** to enhance interpretability and storytelling.  
These dashboards provide a visual comparison of each client’s performance over time, highlighting whether KPIs increased or decreased

🔗 **View the dashboards here:**  
[Tableau Public — A/B Test KPI Dashboard](https://public.tableau.com/app/profile/riccardo.conti)

---

## 🧠 Interpretation and Key Findings
  
- Findings were used to propose **strategic recommendations**, including:  
  - Reallocating marketing budgets toward top-performing channels.  
  - Refining campaign timing and creative assets.  
  - Integrating A/B testing insights into ongoing optimization cycles.

---

