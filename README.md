# Basic-Project-of-Data-Engineering
End-to-end starter for data engineering: ingest an Excel survey, clean &amp; encode features, train baseline ML models (LogReg, Tree, SVM) with reproducible pipelines, save artifacts, and visualize KPIs in an interactive Power BI dashboard. Lightweight, laptop-friendly, fork-ready.
A lightweight, end‑to‑end template that turns a raw Excel survey into a clean dataset, trains baseline ML models, and surfaces insights in a Power BI dashboard.


**1. Project Idea**

We use a real‑world Data‑**Professional Survey** (630 responses) to demonstrate the complete data‑engineering lifecycle on a laptop—no Spark, no cloud.

**Excel → pandas → Scikit‑Learn → Power BI**

The goal is to give newcomers a hands‑on, reproducible example they can fork, run, and extend.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------


**2. Objectives**

**1.Ingest & Explore** – Load the XLSX file, validate schema, profile data quality.

**2.Pre‑process**– One‑hot encode, scale, and split with fixed **random_state.**

**3.Model & Evaluate** – Train Logistic Regression, Decision Tree, and SVM with 5‑fold CV; report Accuracy, F1, ROC‑AUC.

**4.Persist** – Save the best pipeline and model artefacts to **/models.**

**5.Visualise** – Publish key KPIs (salary, job satisfaction, demographics) in the Power BI dashboard (**Dashboard.pbix**).

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**3. Dataset**

- Source: An anonymised Excel survey of data professionals collected in 2024.

- Rows: 630 participants.

- Columns (subset):

1) Country

2) Age

3) Gender

4) Job_Title

5) Annual_Salary_USD

6) Happiness_WorkLife

7) Happiness_Salary

8) Favourite_Language

A 50‑row sample (data/sample_data.csv) is included; the full file can be downloaded from the link in README_DATA.md.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

**4. Requirements**

Python 3.9+ and the packages in requirements.txt (≈ 120 MB install). Power BI Desktop (free) for the dashboard.



**Author: Ahmad Rasheed – Data Scientist**






