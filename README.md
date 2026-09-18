# Hi, I'm Maulik Parmar 👋

### Quantitative Data Scientist & Risk Analytics Specialist | UK Financial Services & Energy Markets

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat&logo=linkedin)](https://linkedin.com)
[![GitHub](https://img.shields.io/badge/GitHub-WarWolf95-181717?style=flat&logo=github)](https://github.com/WarWolf95)
[![Location](https://img.shields.io/badge/Location-United_Kingdom-00247D.svg)](https://en.wikipedia.org/wiki/United_Kingdom)
[![Status](https://img.shields.io/badge/Open_To-Senior_Data_Science_%26_Risk_Roles-brightgreen.svg)]()

Senior Data Scientist specializing in **statistical modeling**, **credit risk scorecards (IRB / Basel II/III)**, **pricing causal inference (A/B testing)**, **time series forecasting**, and **regulatory compliance analytics (FCA Consumer Duty PS22/9)**. 

I bridge the gap between rigorous mathematical modeling, high-performance data engineering (Polars, SQL, SQLite/DuckDB), and executive decision support (Power BI, C-Suite reporting).

---

## 🛠️ Technical Toolkit & Methodological Competencies

| Domain | Methodologies & Frameworks | Technologies & Tools |
| :--- | :--- | :--- |
| **Credit & Conduct Risk** | Probability of Default (PD), WoE / Information Value (IV), Scorecard Scaling (PDO), FCA Consumer Duty (PS22/9, FG22/5), FOS Ombudsman benchmarks | Python, Polars, Scikit-Learn, LightGBM, SQLite, Power BI |
| **Statistical Inference & Causal ML** | A/B Testing, Pre-experiment Power Analysis (MDE), Stratified Block Randomisation, CATE Subgroup Analysis, Benjamini-Hochberg FDR, E-values | Python, Statsmodels, SciPy, Bootstrap Estimation, OpenPyXL |
| **Deep Learning & Forecasting** | Multimodal Time Series, Transformers, Temporal Fusion Transformers, LSTM, FinBERT Financial Sentiment, Walk-Forward Validation | PyTorch, Hugging Face Transformers, XGBoost, Statsmodels |
| **Data Engineering & BI** | Star Schema Relational Modeling, High-Throughput Ingestion, Parquet Pipeline Storage, DAX Measure Optimization | Polars, Pandas, DuckDB, SQLite, Power BI Desktop, Git, CI/CD |

---

## 🚀 Featured Production Projects

```
┌──────────────────────────────────────────────────────────────────────────────────────────────────┐
│                                   PORTFOLIO PROJECT DIRECTORY                                    │
└──────────────────────────────────────────────────────────────────────────────────────────────────┘
```

### 1. [UK Motor Insurance Pricing A/B Test](https://github.com/WarWolf95/pricing-ab-test)
> **Causal Inference, Stratified Randomisation & FCA Consumer Duty Compliance**

*   **Objective:** Pre-registered experimental trial evaluating price elasticity and conversion sensitivity for a UK motor insurer across **124,000 visitor sessions**.
*   **Empirical Results:** Detected a statistically significant **+0.60 pp conversion lift** ($p = 6.62 \times 10^{-5}$) with balanced loss ratios (-1.13 pp) and zero adverse vulnerability outcome disparity.
*   **Tech Stack:** `Python`, `Polars`, `Statsmodels`, `SciPy`, `FCA PS22/9 Data`, `Programmatic Excel Dashboard`.
*   **Key Deliverable:** Pre-experiment power analysis, SMD covariate balance Love Plot, forest plot of heterogeneous treatment effects (CATE), and native formula-driven stakeholder workbook.

---

### 2. [Retail Credit Risk Scorecard Modeling Pipeline](https://github.com/WarWolf95/credit-risk-scorecard-pipeline)
> **Basel II/III IRB Probability of Default (PD) & Scorecard Scaling**

*   **Objective:** Production-grade retail lending credit risk pipeline trained on **2.26 million loan originations**, evaluating default risk under strict temporal segregation (zero post-origination data leakage).
*   **Methodology:** Coarse/fine monotonic Weight of Evidence (WoE) binning, Information Value (IV) ranking, Points-to-Double-the-Odds (PDO = 20) score calibration ($600$ base score at $50:1$ odds).
*   **Model Benchmarking:** Captured **~98% of the discriminative power** of an unconstrained gradient-boosted benchmark (Scorecard AUC: **0.710**, Gini: **0.420**, KS: **31.5%** vs. LightGBM AUC: **0.725**) while retaining 100% linear per-bin Adverse Action auditability.
*   **Tech Stack:** `Python`, `Polars`, `Scikit-Learn`, `LightGBM`, `Matplotlib`, `GitHub Actions CI`.

---

### 3. [FCA Consumer Duty Outcome Monitoring Platform](https://github.com/WarWolf95/consumer-duty-analytics)
> **UK Financial Conduct Authority (PS22/9 / FG22/5) Regulatory Analytics**

*   **Objective:** End-to-end SQL, Python, and Power BI platform monitoring conduct risk across 4 statutory outcome areas: *Products & Services*, *Price & Value*, *Consumer Support*, and *Vulnerability Outcome Disparity*.
*   **Architecture:** 4-Tier hybrid data provenance framework processing 50,000 customer profiles and 75,000 policy sales, benchmarked directly against official FCA GI Value Measures and FOS ombudsman uphold statistics.
*   **Visual Delivery:** 4-Page Power BI executive suite designed with an official FCA Claret theme (`#701B45`), custom DAX measure suite, and automated SQLite Star Schema ingestion.
*   **Tech Stack:** `SQL`, `Python`, `SQLite Star Schema`, `Power BI Desktop`, `FCA / FOS Open Data`.

---

### 4. [Multimodal Deep Learning for Electricity Price Forecasting](https://github.com/WarWolf95/uk-electricity-price-forecasting)
> **Time Series Forecasting & NLP Sentiment Fused with Elexon BMRS Market Data**

*   **Objective:** Wholesale price forecasting across **96,408 half-hourly intervals** (Jan 2020 – Jun 2025), evaluating whether NLP-derived geopolitical sentiment shocks improve prediction during volatile market stress (2022 energy crisis natural experiment).
*   **Data Fusion:** Integrates 7 public data streams: Elexon BMRS grid demand/generation, Sheffield Solar PV, Open-Meteo ERA5 weather, TTF Dutch gas futures, and FinBERT-scored Guardian financial articles.
*   **Findings:** Sentiment features improved Transformer MAE by **~4% during the crisis regime** ($p = 0.018$ Diebold-Mariano test), while statistical baselines (XGBoost) dominated normal operating regimes.
*   **Tech Stack:** `PyTorch`, `Hugging Face (FinBERT)`, `XGBoost`, `Temporal Fusion / Attention Models`, `Statsmodels`.

---

### 5. [UK Workforce Planning & Labour Market Intelligence](https://github.com/WarWolf95/Workforce-Planning-Labour-Market-Intelligence)
> **Macroeconomic Benchmarking, ONS ASHE Earnings & Succession Risk Analysis**

*   **Objective:** Data engineering and analytical auditing platform benchmarking internal organizational rosters against macroeconomic UK labour market supply, ONS ASHE salary medians, and live Adzuna vacancy feeds.
*   **Analytics:** Quantifies skills shortages, detects critical role retirement cliffs (e.g. 41% 5-year retirement risk in specialist engineering), and isolates internal salary gaps (e.g. -26.3% London software developer lag).
*   **Tech Stack:** `Python`, `SQLite/DuckDB Star Schema`, `Scikit-Learn TF-IDF`, `ONS / Nomis API`, `Power BI`.

---

## 📈 GitHub Statistics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=WarWolf95&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Maulik's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=WarWolf95&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</p>

---

## 📬 Contact & Professional Links

*   **Email:** Available via GitHub Profile
*   **Location:** United Kingdom
*   **Specialties:** Credit Risk Scorecards | Causal Inference & Pricing | Statistical Forecasting | FCA Regulatory Conduct

---

*© 2026 Maulik Parmar. All source code and research methodologies are released under the [MIT License](LICENSE).*
