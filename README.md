<div align="center">

  <img src="./assets/header.svg" width="100%" alt="Haider Ali - Data Scientist & Analytics Engineer" />

  <p align="center">
    <a href="https://haiderdaportfolio.vercel.app"><b>🌐 Portfolio</b></a> &nbsp;•&nbsp;
    <a href="mailto:haydermuhib@tutamail.com"><b>✉️ Email</b></a> &nbsp;•&nbsp;
    <a href="https://github.com/haydermuhib"><b>🐙 GitHub</b></a> &nbsp;•&nbsp;
    <b>🐧 Fedora Linux</b>
  </p>

  <p align="center">
    <a href="https://marimo.io" target="_blank" rel="noreferrer" title="Marimo">
      <img src="https://marimo.io/logo.png" width="42" height="42" alt="Marimo" />
    </a>
    &nbsp;&nbsp;
    <a href="https://pixi.sh" target="_blank" rel="noreferrer" title="Pixi">
      <img src="https://pixi.prefix.dev/latest/assets/pixi-logo.svg" width="42" height="42" alt="Pixi" />
    </a>
    &nbsp;&nbsp;
    <a href="https://duckdb.org" target="_blank" rel="noreferrer" title="DuckDB">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/duckdb/duckdb-original.svg" width="42" height="42" alt="DuckDB" />
    </a>
    &nbsp;&nbsp;
    <a href="https://www.postgresql.org" target="_blank" rel="noreferrer" title="PostgreSQL">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" width="42" height="42" alt="PostgreSQL" />
    </a>
    &nbsp;&nbsp;
    <a href="https://pandas.pydata.org" target="_blank" rel="noreferrer" title="Pandas">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" width="42" height="42" alt="Pandas" />
    </a>
    &nbsp;&nbsp;
    <a href="https://seaborn.pydata.org" target="_blank" rel="noreferrer" title="Seaborn">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/seaborn/seaborn-original.svg" width="42" height="42" alt="Seaborn" />
    </a>
    &nbsp;&nbsp;
    <a href="https://www.python.org" target="_blank" rel="noreferrer" title="Python">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="42" height="42" alt="Python" />
    </a>
    &nbsp;&nbsp;
    <a href="https://scikit-learn.org" target="_blank" rel="noreferrer" title="Scikit-Learn">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/scikitlearn/scikitlearn-original.svg" width="42" height="42" alt="Scikit-Learn" />
    </a>
  </p>

</div>

---

### ⚡ Snapshot

* 🎓 **Academic:** BS in Data Science
* 🔬 **Modern Standard:** Building next-generation data science systems with **Marimo** (reactive, git-friendly computing), **Pixi** (fast, deterministic Rust-backed environments), and **DuckDB** (in-process analytical SQL)
* 📊 **Focus Areas:** Product Analytics, Customer Lifecycle (Cohort/RFM), Statistical Experimentation & Supervised ML

---

### 🚀 Featured Case Studies & Systems

#### ⚡ [CardioPulse: Clinical Risk & Readmission Intelligence](https://github.com/haydermuhib/hospital-readmission-marimo)
> **Flagship Showcase:** Marimo Reactive Web App • Pixi • DuckDB • Scikit-Learn • Plotly  
> **Dataset Scale:** 100,000 Inpatient Encounters (Compressed to 533 KB Columnar Parquet)

* **High-Throughput Analytics:** Sub-50ms queries directly over columnar Parquet via **DuckDB**, bypassing heavy database overhead.
* **Modern Reactive Architecture:** Built entirely as a reproducible, git-friendly **Marimo** reactive application managed deterministically with **Pixi**.
* **Predictive Performance:** Class-balanced `HistGradientBoosting` model achieving **0.804 ROC-AUC**, capturing 78.5% of high-risk readmissions before discharge.
* **Production Integrity:** Backed by 17 automated unit tests covering ETL pipelines, DuckDB SQL queries, and Plotly interactive charts.

[![Live App](https://img.shields.io/badge/Live_App-Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)](https://huggingface.co/spaces/haydermuhib/hospital-readmission-marimo)
[![Source Code](https://img.shields.io/badge/Source-GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/haydermuhib/hospital-readmission-marimo)

---

#### 🛒 [E-Commerce Product Analytics & Experimentation Engine](https://github.com/haydermuhib/01_ecommerce_product_analytics)
> **Discipline:** Supervised ML (Churn Classification) • Statistical A/B Testing • Product Growth Analytics  
> **Dataset Scale:** 540,000+ Real International Retail Transactions • SQLite Analytical Engine

* **Cohort Dynamics:** Modeled monthly retention decay, uncovering an immediate 60% attrition drop in the first 30 days that stabilizes into predictable buying cadence.
* **Pareto Revenue Concentration:** Isolated VIP Champions who generate >35% of total gross revenue despite representing <8% of the customer base.
* **Hypothesis Testing Simulator:** Built an interactive A/B testing simulator with Two-Sample Z-proportion tests, critical rejection boundaries, and statistical power curves.
* **Predictive Churn Engine:** Deployed a Scikit-Learn Random Forest churn classifier within a custom Neumorphic Dark Streamlit interface.

[![Live App](https://img.shields.io/badge/Live_App-Streamlit_Cloud-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)](https://01ecommerce-analytics.streamlit.app/)
[![Source Code](https://img.shields.io/badge/Source-GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/haydermuhib/01_ecommerce_product_analytics)

---

#### 👥 [User Cohort & RFM Lifecycle Analytics](https://github.com/haydermuhib/02_user_cohort_rfm_analytics)
> **Discipline:** Customer Lifecycle Diagnostics • CRM Retention Strategy • Behavioral Segmentation  
> **Dataset Scale:** Multi-Market International Retail Purchasing • 12+ Month Window

* **Retention Cliff Identification:** Quantified acquisition decay from 100% to 20%–25% by month 1, establishing the first 30 days as the highest-leverage retention window.
* **Customer Segmentation:** Quintile scoring across Recency, Frequency, and Monetary dimensions to classify customers into actionable CRM tiers (Champions, Loyal, At-Risk, Hibernating).
* **Data Integrity:** Isolated guest checkout anomalies (24% of volume) to safeguard cohort matrix integrity against behavioral distortion.

[![Live App](https://img.shields.io/badge/Live_App-Streamlit_Cloud-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)](https://02usercohortrfmanalytics.streamlit.app/)
[![Source Code](https://img.shields.io/badge/Source-GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/haydermuhib/02_user_cohort_rfm_analytics)

---

#### 🏢 [People Analytics: Employee Exit Survey Diagnostics](https://github.com/haydermuhib/03_employee_exit_surveys)
> **Discipline:** Workforce Intelligence • Cross-Institutional Survey Harmonization • Career Vulnerability  
> **Dataset Scale:** 6,600+ Raw Survey Records • 3,868 Voluntary Resignations (DETE vs. TAFE)

* **Tenure Vulnerability:** Discovered that veteran personnel (11+ years of service) resign due to dissatisfaction at 1.6x the rate of early-career employees (52.6% vs. 32.6%).
* **Institutional Friction Disparity:** Quantified structural workload fatigue and administrative friction, showing DETE exhibited 46.5% resignation dissatisfaction vs. 30.2% in TAFE.
* **Schema Normalization:** Standardized two disparate institutional survey architectures into a high-performance Apache Parquet datastore.

[![Live App](https://img.shields.io/badge/Live_App-Streamlit_Cloud-FF4B4B?style=flat-square&logo=streamlit&logoColor=white)](https://03employeeexitsurveys.streamlit.app/)
[![Source Code](https://img.shields.io/badge/Source-GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/haydermuhib/03_employee_exit_surveys)

---

### ⚡ Infrastructure & Pipeline Tools

* **[learn-duckdb](https://github.com/haydermuhib/learn-duckdb):** In-process analytical SQL benchmarks, columnar Parquet scanning, and query plan optimization.
* **[GMapsScraper](https://github.com/haydermuhib/GMapsScraper):** High-throughput multithreaded CLI extraction engine for spatial lead intelligence.

---

### 📈 GitHub Analytics

<div align="center">
  <a href="https://github.com/haydermuhib">
    <img src="https://github-readme-stats-eight-theta.vercel.app/api?username=haydermuhib&show_icons=true&theme=tokyonight&hide_border=true&count_private=true#gh-dark-mode-only" alt="Haider's GitHub Stats" />
    <img src="https://github-readme-stats-eight-theta.vercel.app/api?username=haydermuhib&show_icons=true&theme=default&hide_border=false&count_private=true#gh-light-mode-only" alt="Haider's GitHub Stats" />
  </a>
  &nbsp;&nbsp;
  <a href="https://github.com/haydermuhib">
    <img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=haydermuhib&layout=compact&theme=tokyonight&hide_border=true#gh-dark-mode-only" alt="Top Languages" />
    <img src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=haydermuhib&layout=compact&theme=default&hide_border=false#gh-light-mode-only" alt="Top Languages" />
  </a>
</div>

<div align="center">
  <br/>
  <a href="https://github.com/haydermuhib">
    <img src="https://streak-stats.demolab.com/?user=haydermuhib&theme=tokyonight&hide_border=true#gh-dark-mode-only" alt="GitHub Streak" />
    <img src="https://streak-stats.demolab.com/?user=haydermuhib&theme=default&hide_border=false#gh-light-mode-only" alt="GitHub Streak" />
  </a>
</div>

<br/>

<div align="center">
  <img src="./assets/footer.svg" width="100%" alt="Footer" />
</div>
