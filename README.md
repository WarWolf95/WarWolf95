# Maulik Parmar

Data Analyst & BI Developer based in London, United Kingdom.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://linkedin.com)
[![GitHub](https://img.shields.io/badge/GitHub-WarWolf95-181717?style=flat&logo=github)](https://github.com/WarWolf95)
[![Web Portfolio](https://img.shields.io/badge/Web_Portfolio-warwolf95.github.io-3B82F6?style=flat&logo=googlechrome&logoColor=white)](https://warwolf95.github.io)
[![Location](https://img.shields.io/badge/Location-London%2C_UK-00247D.svg)](https://en.wikipedia.org/wiki/London)
[![Email](https://img.shields.io/badge/Email-maulik.workstuff%40gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:maulik.workstuff@gmail.com)

Data Analyst with over 6.5 years of experience at Numerator, a US consumer intelligence firm serving enterprise retail accounts. Experienced in building interactive Power BI dashboards (DAX, dimensional modelling), writing complex SQL (MySQL, PostgreSQL, CTEs, window functions), and automating operational data pipelines with Python. 

Recently completed an MSc in Data Science at Coventry University with applied project work in financial compliance, risk scoring, labour market intelligence, and time series forecasting.

---

## Technical Skills

* **BI & Dashboarding:** Power BI (Advanced DAX, Power Query, Star Schema, Data Modelling), Excel (Power Pivot, native formulas, VBA), Tableau
* **Databases & Querying:** MySQL, PostgreSQL, SQLite, DuckDB, query performance optimisation, relational schema design
* **Data Manipulation & Scripting:** Python (Polars, Pandas, NumPy, SciPy, Statsmodels), REST APIs, automation scripts
* **Analytical Methods:** A/B testing, exploratory data analysis, cohort analysis, Weight of Evidence (WoE), time series analysis
* **Quality & Governance:** Data quality assurance, SLA tracking, root cause analysis, UK GDPR / Data Protection Act 2018
* **Workflow Tools:** Git, GitHub Actions, JIRA, Salesforce, pytest

---

## Professional Experience

### Data Associate Lead - Analytics & Client Operations | Numerator
*April 2018 – November 2024*

Numerator is a US-based consumer intelligence firm providing market data and retail analytics to enterprise brands.
* **Workflow Automation:** Automated data processing tasks using Python scripts and scheduled MySQL queries, cutting turnaround times by 35% and enabling same-day reporting refreshes.
* **BI Dashboard Development:** Built interactive Power BI dashboards with custom DAX calculations and dimensional models, delivering consumer purchasing insights that improved client contract retention by 12% across 15 enterprise retail accounts.
* **Client & Incident Management:** Acted as the main technical contact for 15+ retail accounts, translating commercial questions into reporting requirements and managing data quality issues through JIRA and Salesforce (maintained 98%+ client satisfaction).
* **Quality Assurance:** Standardised data verification checks across production workflows, reducing downstream reporting discrepancies by 15%.
* **SQL Query Optimisation:** Tuned multi-table JOINs, indexing, and CTE structures across multi-million-row transactional tables, improving report query speeds by 30%.
* **Team Coaching:** Mentored 4 junior analysts on SQL writing, dashboard design, and QA standards, helping increase overall team throughput by 25%.
* **Recognition:** Awarded Star Performer, Spot Award, and High Impact Award for accuracy, work ethic, and leadership.

---

## Projects

### 1. [FCA Consumer Duty Outcome Monitoring Platform](https://github.com/WarWolf95/consumer-duty-analytics)
**Tools:** SQL, Python, SQLite Star Schema, Power BI, DAX

An analytics solution designed to help financial services firms monitor and evidence customer outcomes under FCA regulations (PS22/9).
* Modeled 50,000 customer records, 75,000 policy sales, and 10,000 complaints in an automated SQLite star schema.
* Benchmarked internal company metrics against published FCA General Insurance Value Measures and Financial Ombudsman Service (FOS) data.
* Created a 4-page Power BI dashboard tracking claims ratios, SLA resolution times, and operational outcome gaps for vulnerable customers.

---

### 2. [UK Motor Insurance Pricing A/B Test](https://github.com/WarWolf95/pricing-ab-test)
**Tools:** Python, Polars, Statsmodels, SciPy, Programmatic Excel, pytest

An end-to-end pricing experiment for a UK motor insurance book, testing price elasticity across 124,000 visitor sessions.
* Established sample size and statistical power parameters before the trial (MDE = 0.50 pp lift at 80% power).
* Tested primary conversion differences using proportion z-tests and verified demographic balance between test arms.
* Evaluated customer subgroup responses using false discovery rate corrections to verify fair treatment across vulnerability drivers.
* Generated an 8-sheet stakeholder Excel workbook built with native formulas and what-if sensitivity tables.

---

### 3. [Retail Credit Risk Scorecard Modeling Pipeline](https://github.com/WarWolf95/credit-risk-scorecard-pipeline)
**Tools:** Python, Polars, Scikit-Learn, LightGBM, Matplotlib

A credit risk scoring pipeline trained on 2.26 million consumer loan records, designed around Basel II and UK regulatory principles.
* Enforced strict anti-data-leakage rules, filtering out post-origination columns so only application-time attributes were used.
* Applied monotonic Weight of Evidence (WoE) binning and Information Value (IV) rankings to select risk drivers.
* Calibrated a logistic regression scorecard scaled to 600 base points (Points to Double the Odds = 20), capturing ~98% of the predictive power of a LightGBM model while remaining fully auditable.
* Validated score distributions and discrimination curves (ROC, PR, Calibration) on out-of-time test data.

---

### 4. [UK Workforce Planning & Labour Market Intelligence](https://github.com/WarWolf95/Workforce-Planning-Labour-Market-Intelligence)
**Tools:** Python, SQLite, Scikit-Learn, Power BI, ONS & Nomis APIs

An analytical database and reporting dashboard comparing organizational workforce records with national UK economic indicators.
* Ingested and combined official salary benchmarks from the ONS Annual Survey of Hours and Earnings (ASHE) with vacancy data.
* Highlighted internal-to-market salary gaps (such as a -26.3% gap for London software developers) and identified critical departments facing 5-year retirement risks.
* Built a 3-page Power BI report tracking headcount, regional wage differences, and succession readiness.

---

### 5. [UK Electricity Price Forecasting](https://github.com/WarWolf95/uk-electricity-price-forecasting)
**Tools:** Python, PyTorch, XGBoost, Transformers, Statsmodels

A market analytics project examining wholesale electricity price behaviour across 96,408 half-hourly intervals from 2020 to 2025.
* Merged public grid data from Elexon BMRS (demand and fuel mix) with historical weather observations and natural gas futures.
* Analyzed financial news articles using FinBERT to test whether geopolitical sentiment shocks helped improve price forecasts during the 2022 energy crisis.
* Evaluated performance across statistical baselines (ARIMA, XGBoost) and neural architectures.

---

## Education & Certifications

* **MSc in Data Science** | Coventry University, UK (2026)
  * *Coursework:* Statistical Modelling, Machine Learning, Predictive Analytics, Data Governance
  * *Leadership:* Elected Course Representative for MSc Data Science cohort (2025–2026)
* **BEng in Electrical Engineering** | Gujarat Technological University, India (2017)
* **Google Data Analytics Professional Certificate**

---

## Profile Summary

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=WarWolf95&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=WarWolf95&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</p>

---

## Contact

* **Location:** London, United Kingdom
* **GitHub:** [github.com/WarWolf95](https://github.com/WarWolf95)
* **Email:** [maulik.workstuff@gmail.com](mailto:maulik.workstuff@gmail.com)

---

*All projects in this portfolio are published under the [MIT License](LICENSE).*
