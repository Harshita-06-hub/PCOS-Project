# PCOS Clinical Data Analytics Pipeline
**Role:** Data Analyst & Researcher  
**Focus:** Clinical Data Standardization, Exploratory Data Analysis (EDA), & Reproducible Research

---

### 🎯 The Business/Clinical Problem
Clinical datasets are notoriously messy, characterized by heterogeneous variables, missing values, and inconsistent formatting. This project establishes a **standardized, modular R-based pipeline** to transform raw clinical PCOS records into actionable insights, enabling disease stratification and data-driven hypothesis generation.

### 🚀 Key Technical Highlights
* **Reproducible Workflow:** Designed a modular pipeline (`data_cleaning.R` → `eda.R` → `visuals.R`) using `tidyverse` standards, ensuring the analysis is auditable and scalable.
* **Data Sanitization:** Implemented rigorous cleaning protocols for clinical variables, including numeric conversion of BMI/hormonal profiles, factor-level harmonization, and outlier management.
* **Statistical Visualization:** Utilized `ggplot2` to generate high-fidelity clinical markers (LH/FSH ratios, insulin dynamics, BMI stratification), identifying phenotypic variance between cohorts.
* **Automated Reporting:** Leveraged `RMarkdown` to bridge the gap between raw data processing and final interpretable reporting.

### 🛠 Tech Stack
* **Language:** R (Expert: Biostatistics, Data Automation)
* **Framework:** `tidyverse` (dplyr, tidyr, readr)
* **Visualization:** `ggplot2` (custom themes & aesthetic mapping)
* **Workflow:** `RMarkdown` (Automated report generation)

### 📈 Analytical Workflow
| Phase | Objective | Output |
| :--- | :--- | :--- |
| **Data Cleaning** | Sanitize & structure raw records | Cleaned clinical dataset |
| **EDA** | Comparative phenotypic analysis | Cohort-specific insights |
| **Visualization** | Feature correlation heatmaps | Stratification markers |

### 🚀 How to Run
```bash
# 1. Install dependencies
install.packages(c("tidyverse", "ggplot2"))

# 2. Execute pipeline
# Run in sequence: data_cleaning.R -> eda.R -> visuals.R
# OR knit the RMarkdown report to generate the full automated analysis.
