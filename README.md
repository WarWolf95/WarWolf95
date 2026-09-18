# Maulik Parmar

Data Analyst based in the United Kingdom.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://linkedin.com)
[![GitHub](https://img.shields.io/badge/GitHub-WarWolf95-181717?style=flat&logo=github)](https://github.com/WarWolf95)
[![Location](https://img.shields.io/badge/Location-United_Kingdom-00247D.svg)](https://en.wikipedia.org/wiki/United_Kingdom)

I work with SQL, Python, Power BI, and Excel to analyse data, build dashboards, and help teams make decisions backed by numbers. My work focuses on financial services, regulatory reporting (FCA Consumer Duty), credit risk analysis, pricing experiments, and market data.

---

## Technical Skills

* **Data Analysis & Scripting:** Python (Polars, Pandas, NumPy, SciPy, Statsmodels)
* **Databases & Querying:** SQL, SQLite, DuckDB, relational modeling, Star Schema design
* **Business Intelligence & Reporting:** Power BI Desktop, DAX, Excel (native formulas, modeling), automated reporting
* **Analytical Methods:** A/B testing and hypothesis testing, cohort analysis, exploratory data analysis, data validation and testing, time series analysis
* **Tools & Workflow:** Git, GitHub Actions, virtual environments, pytest

---

## Projects

### 1. [FCA Consumer Duty Outcome Monitoring Platform](https://github.com/WarWolf95/consumer-duty-analytics)
**Tools:** SQL, Python, SQLite Star Schema, Power BI, DAX

An end-to-end analytics platform built to help financial firms monitor customer outcomes under the FCA Consumer Duty regulations (PS22/9).
* Processed 50,000 customer records, 75,000 policy sales, and 10,000 complaints through an automated SQLite pipeline.
* Benchmarked internal company numbers against published data from the Financial Conduct Authority (GI Value Measures) and the Financial Ombudsman Service (FOS).
* Built an interactive 4-page Power BI dashboard covering products and services, fair value, customer support resolution times, and outcome differences for vulnerable customers.

---

### 2. [UK Motor Insurance Pricing A/B Test](https://github.com/WarWolf95/pricing-ab-test)
**Tools:** Python, Polars, Statsmodels, SciPy, Excel, pytest

An end-to-end pricing experiment for a UK car insurance portfolio, evaluating customer response to risk-adjusted rates.
* Carried out sample size and power calculations before the trial across 124,000 visitor sessions (62,000 per test group).
* Tested conversion rate changes using two-sample proportion tests and checked balance across customer regions and devices.
* Measured customer subgroup responses using false discovery rate corrections to make sure vulnerable groups were treated fairly.
* Exported all findings into a structured, formula-driven Excel workbook designed for business stakeholders.

---

### 3. [Credit Risk Analysis & Scorecard Modeling](https://github.com/WarWolf95/credit-risk-scorecard-pipeline)
**Tools:** Python, Polars, Scikit-Learn, LightGBM, Matplotlib

A credit risk data pipeline built on 2.26 million consumer loan records to evaluate default risk and score borrowers.
* Prepared and cleaned data strictly using information known at the time of application to prevent data leakage.
* Binned credit variables and calculated Weight of Evidence (WoE) and Information Value (IV) to find the most useful predictors.
* Built a traditional credit scorecard using logistic regression scaled to 600 base points (Points to Double the Odds = 20), comparing its performance directly against LightGBM.
* Generated score distributions and validation curves (ROC, Precision-Recall, Calibration) on out-of-time test data.

---

### 4. [UK Workforce Planning & Labour Market Intelligence](https://github.com/WarWolf95/Workforce-Planning-Labour-Market-Intelligence)
**Tools:** Python, SQLite, Scikit-Learn (TF-IDF), Power BI, ONS & Nomis APIs

An analytics database and dashboard designed to compare internal staff rosters with national UK employment and salary benchmarks.
* Extracted and merged official earnings data from the ONS Annual Survey of Hours and Earnings (ASHE) with job vacancy postings.
* Identified regional salary gaps across job roles (such as London software developer pay gaps) and highlighted departments facing retirement risks over a 5-year horizon.
* Designed a 3-page Power BI report with custom DAX measures for headcount, salary differences, and succession planning.

---

### 5. [UK Electricity Price Forecasting](https://github.com/WarWolf95/uk-electricity-price-forecasting)
**Tools:** Python, PyTorch, XGBoost, Transformers, Statsmodels

A time series analysis project looking at UK wholesale electricity prices across 96,408 half-hourly periods between 2020 and 2025.
* Merged public market data from Elexon BMRS (system demand, fuel generation mix) with weather archives and gas futures prices.
* Scored financial news articles using FinBERT to test whether news sentiment helps predict price spikes during market stress like the 2022 energy crisis.
* Evaluated multiple models including baseline ARIMA, XGBoost, and attention-based models across crisis holdout and walk-forward periods.

---

## Profile Summary

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=WarWolf95&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=WarWolf95&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</p>

---

## Contact

* **Location:** United Kingdom
* **GitHub:** [github.com/WarWolf95](https://github.com/WarWolf95)
* **Focus Areas:** Regulatory Reporting, SQL Analysis, Dashboard Design, Business Analytics

---

*All code repositories in this portfolio are open source and published under the [MIT License](LICENSE).*
