# 📊 BCSE331L – Exploratory Data Analysis Course Project (Fall 2025–26)

This repository contains the complete project work for the course **BCSE331L – Exploratory Data Analysis (EDA)** offered at **VIT University**. The project explores real-world suicide data in China and involves end-to-end data handling, from cleaning and transformation to visualization, clustering, and model development.

---

## 🧑‍🎓 Student Information

- **Name:** Parth Suri  
- **Registration No.:** 22BDS0116  
- **Specialization:** B.Tech CSE – Data Science  
- **Course Code:** BCSE331L  
- **Instructor:** Dr. Prakash M

---

## 🗂️ Dataset Overview

- **Dataset Name:** SuicideChina.csv  
- **Source:** [GitHub - Prakash Salem](https://raw.githubusercontent.com/salemprakash/EDA/main/Data/SuicideChina.csv)  
- **Description:** Contains anonymized suicide records from rural and urban China over several years.  
- **Key Attributes:**
  - `Person_ID`, `Sex`, `Age`, `Education`, `Occupation`, `Urban`, `Hospitalised`, `Died`
  - `Method`, `Year`, `Month` (Time variables)

---

## 🎯 Project Objectives

- Understand the scope of exploratory data analysis on real-world data
- Perform data cleaning, transformation, and summarization
- Apply statistical and visual techniques for pattern discovery
- Develop simple models for insights and trend detection
- Use clustering and dimensionality reduction on multidimensional data
- Generate actionable insights using Python libraries

---

## 🧱 Project Structure

| Phase | Module | Focus |
|-------|--------|-------|
| **Phase I** | Module 1–3 | Data Cleaning, Summary Stats, Univariate, Bivariate & Multivariate Analysis |
| **Phase II** | Module 4–5 | Visualization Techniques, Advanced Stats, Time Series, Clustering |
| **Phase III** | Module 6–8 | Dimensionality Reduction, Regression, Model Evaluation, Report Generation |

---

## 📌 Key Techniques Used

- **Data Handling:** Deduplication, Binning, Missing Value Treatment
- **Statistical Analysis:** Descriptive statistics, correlation, contingency tables
- **Visualization:** Bar plots, Histograms, Scatter plots, Catplots, Pairplots
- **Clustering:** Hierarchical, Model-Based, Spectral, Outlier Detection
- **Dimensionality Reduction:** PCA, SVD, Factor Analysis, t-SNE (optional)
- **Model Development:** Linear Regression, Accuracy Evaluation

---

## 🛠️ Tools & Libraries

- Python 3.x  
- Google Colab  
- Pandas, NumPy  
- Seaborn, Matplotlib  
- Scikit-learn  
- Plotly (optional for interactive visuals)

---

## 📄 Deliverables

- `22BDS0116.ipynb` – All code notebooks for all phases
- Visualizations embedded with markdown explanations
- Final project report (PDF upload in VTOP)
- GitHub link submission for each phase via Google Forms

---

## 🗓️ Timeline

| Phase | Deadline | Marks |
|-------|----------|-------|
| Phase I  | 15th August 2025 | 5 |
| Phase II | 2nd October 2025 | 5 |
| Phase III + Report | 10th November 2025 | 10 (5 + 5) |

---

## 📑 Master Checklist — BCSE331L Exploratory Data Analysis Project  
  
---
**✅ Phase 1 — Till Multivariate Analysis**

- [x] **Dataset Loading & Overview**  
  - Imported dataset from given GitHub URL.  
  - Displayed first few rows and dataset shape (rows × columns).  

- [x] **Data Summary & Metadata**  
  - Summary statistics for numerical variables (mean, median, std, min, max).  
  - Summary for categorical variables (unique values, top categories).  
  - Checked distributions of numerical and categorical variables.  

- [x] **Data Cleaning & Handling**  
  - Checked and reported missing values per column.  
  - Identified and handled duplicates (if any).  
  - Documented treatment of missing/invalid data (drop, impute, etc.).  

- [x] **Univariate Analysis**  
  - Plots: histograms, density plots for numerical features.  
  - Plots: bar plotsfor categorical features.  
  - Identified skewness, outliers, and basic data distribution insights.  

- [x] **Bivariate Analysis**  
  - Numerical vs Numerical: scatter plots, correlation matrix.  
  - Numerical vs Categorical: grouped box plots, grouped bar plots.  

- [x] **Multivariate Analysis**  
  - Pairplots of key numeric variables.  
  - Heatmap of correlations (numeric variables).  
  - Explored 3-way interactions or grouped summaries.  

- [x] **Observations / Notes Written**  
  - Key insights documented (e.g., high correlations, skewed variables, categorical imbalance).  
  - Mentioned potential issues (outliers, data imbalance, missingness).  

- [ ] **Notebook Saved to GitHub**  
  - Verified that outputs and code are visible in GitHub (not just empty code cells).  

---

**✅ Phase 2 — Module 4 & 5: Advanced EDA, Time Series & Clustering**  

- [x] **1D Statistical Analysis**  
  - Skewness, quantiles (Q1, median, Q3, IQR).  
  - Frequency distributions for numerical + categorical features.  
  - Boxplots and violin plots.  
  - Outlier detection (1.5×IQR rule).  

- [x] **2D Statistical Analysis**  
  - Numerical vs Numerical: scatter + regression, correlation heatmap.  
  - Numerical vs Categorical: grouped box/violin plots, group stats.  
  - Categorical vs Categorical: contingency tables, stacked bar plots, chi-square test.  

- [x] **3D Analysis**  
  - 3D scatter plots for top 3 numeric features.  
  - Grouped box/violin plots with categorical coloring.  

- [x] **Time Series Analysis (if applicable)**  
  - Detected year/date column and converted to datetime index.  
  - Annual resampling and trend visualization.  
  - Rolling mean/log transform for smoothing.  
  - Grouped trends by categorical feature.  

- [x] **Clustering (Module 5)**  
  - Feature selection and scaling.  
  - **KMeans**: elbow + silhouette, cluster centers, PCA visualization.  
  - **Agglomerative**: dendrogram, cluster counts.  
  - **Gaussian Mixture (GMM/EM)**: BIC/AIC selection, cluster results.  
  - Attached cluster labels back to dataset and summarized cluster profiles.  

- [x] **Outlier Detection**  
  - IQR-based detection.  
  - Local Outlier Factor (LOF).  
  - DBSCAN density-based outliers.  

- [x] **Observations / Notes Written**  
  - Interpreted skewness/outliers in 1D.  
  - Explained key correlations in 2D.  
  - Commented on 3D scatter grouping.  
  - Documented time series patterns (if applicable).  
  - Explained clustering results & differences across methods.  
  - Noted outliers and treatment suggestions.  

- [x] **Notebook Saved to GitHub**  
  - Verified that Phase 2 outputs and results are visible in repo.  

---

✅ **Ready for Evaluation:** Phase 1 + Phase 2 tasks completed, results documented, and notebook committed to GitHub.  


---

## ✅ Status

- [x] Phase 1: Completed and submitted  
- [x] Phase 2: Completed and submitted  
- [ ] Phase 3: In progress

---

## 📬 Contact

For queries related to this project:  
📧 Email: [parthsuri009@gmail.com](mailto:parthsuri009@gmail.com)  
📌 GitHub: [https://github.com/PSURI1894](https://github.com/PSURI1894)

---

> _This project is a part of academic coursework at Vellore Institute of Technology (VIT), and all rights are reserved for educational use only._

