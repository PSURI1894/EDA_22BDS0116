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

- **Data Handling:** Deduplication, Binning, Missing-value Treatment
- **Statistical Analysis:** Descriptive stats, Correlation, Contingncy Tables
- **Visualization:** Histograms, Boxplots, Heatmaps, Pairplots, 3-D Scatter Plots
- **Clustering:** K-Means, Agglomerative, Gaussian Mixture, Outlier Detection
- **Dimensionality Reduction:** PCA, SVD, Factor Analysis
- **Regression Models:** Linear, Ridge (L2), Lasso (L1)
- **Evaluation Metrics:** R², RMSE, MAE, Cross-Validation Scores

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

---

**✅ Phase 3 — Modules 6 & 7: Dimensionality Reduction & Model Development**

- [x] **Dimensionality Reduction**
  - Applied Principal Component Analysis (PCA) and visualized explained variance.
  - Performed Factor Analysis (FA) for latent variable identification.
  - Interpreted component loadings and factor strengths.
  - Used PCA-transformed data for visualization and model input.

- [x] **Model Development & Evaluation**
  - Defined target variable Died (0 = Survived, 1 = Fatal).
  - Implemented regression models: Linear, Ridge (L2), Lasso (L1).
  - Standardized features and used polynomial transformations for feature interactions.
  - Evaluated models using R², RMSE, MAE, and cross-validation.
  - Selected Ridge Regression as final model (R² ≈ 0.69 CV).

- [x] **Model Interpretation**
  - Identified significant predictors: Hospitalised, Age, Method_Pesticide, Occupation_Farming.
  - Discussed model strengths, stability, and limitations.
  - Plotted Actual vs Predicted and Residuals distributions.

- [x] **Reinforcement Learning (Conceptual Overview)**
  - Compared Supervised vs Reinforcement Learning frameworks.
  - Discussed RL components: Agent, State, Action, Reward, Policy.
  - Related RL to healthcare policy optimization and adaptive intervention strategies.

- [x] **Documentation & Reporting**
  - Added detailed Markdown summaries (Model Evaluation + RL Overview).
  - Prepared final Phase 3 report summarizing all modules (2–7).
  - Report exported as PDF (22BDS0116_ParthSuri_EDA_Report.pdf).

- [x] **Final Verification**
  - All outputs and graphs visible in GitHub version of notebook.
  - Report and notebook submitted before 10 Nov 2025 dea
  
## 🚀 Phase Highlights — BCSE331L Exploratory Data Analysis Project

---

### 🧩 **Phase 1 — Data Cleaning & Multivariate Analysis (Modules 1–3)**

#### **Module Overview**
This phase focused on understanding the dataset, cleaning inconsistencies, and exploring one-dimensional, two-dimensional, and multi-dimensional relationships through visual and statistical methods.

#### **Key Steps**
- **Dataset Exploration:** Loaded and verified `SuicideChina.csv`, analyzed dimensions, column types, and null counts.  
- **Data Cleaning:** Removed duplicates, standardized categorical values, and handled missing data.  
- **Univariate Analysis:** Analyzed individual variable distributions using histograms, KDE plots, and boxplots.  
- **Bivariate & Multivariate Analysis:** Explored relationships (`Age` vs `Died`, `Occupation` vs `Method`) and visualized correlations via heatmaps and pairplots.

#### **Key Findings**
- Majority of suicide cases occurred among **rural, farming populations**.  
- **Hanging** and **pesticide ingestion** emerged as dominant methods.  
- **Age** showed a right-skewed distribution (middle-aged and elderly more prone).  
- Strong correlation observed between **Occupation** and **Method**, indicating occupational exposure influence.

---

### 📊 **Phase 2 — Advanced EDA, Time Series & Clustering (Modules 4–5)**

#### **Module Overview**
Phase 2 deepened the analysis through advanced visualization, time series insights, and clustering to identify hidden behavioral patterns.

#### **Module 4 – Advanced Visualization & Statistical Analysis**
- Performed **1D, 2D, and 3D analyses** with statistical depth.  
- Used **boxplots, violin plots, regression plots**, and **catplots** for rich visual storytelling.  
- Identified **outliers** using IQR and **skewness-based metrics**.  
- Constructed **contingency tables** and applied **Chi-square tests** for categorical dependency.

#### **Module 5 – Clustering & Outlier Detection**
- Implemented multiple clustering algorithms:  
  - **K-Means:** Optimal clusters via Elbow + Silhouette methods.  
  - **Agglomerative:** Hierarchical dendrogram-based grouping.  
  - **GMM (EM):** Compared clusters using BIC/AIC criteria.  
- Conducted **Outlier Detection** using IQR, DBSCAN, and Local Outlier Factor (LOF).

#### **Key Findings**
- K-Means formed **3 major behavioral clusters**:
  - **Cluster 1:** Elderly farmers using pesticide methods.  
  - **Cluster 2:** Middle-aged females using non-chemical methods.  
  - **Cluster 3:** Younger, hospitalized individuals with higher survival rates.  
- Outliers corresponded to **rare urban cases or unusual methods**.  
- No major seasonal pattern but visible rural-urban disparity.

---

### 🧠 **Phase 3 — Dimensionality Reduction & Model Development (Modules 6–7)**

#### **Module 6 – Dimensionality Reduction**
- Applied **PCA** to reduce correlated numeric features.  
- Identified dominant components: `Age`, `Occupation`, `Method`.  
- Performed **Factor Analysis** to uncover **latent behavioral and socio-economic dimensions**.  
- Visualized explained variance and factor loadings through heatmaps.

#### **Module 7 – Model Development & Evaluation**
- Developed regression models to predict **fatality likelihood (`Died`)**.  
- Compared **Linear Regression**, **Ridge (L2)**, and **Lasso (L1)**.  
- Regularization (Ridge) improved model stability and generalization.  
- Achieved cross-validation **R² ≈ 0.695 ± 0.05**.

#### 📈 **Model Performance Summary**

| Model | R² | RMSE | MAE | Remarks |
|:--|:--:|:--:|:--:|:--|
| Linear Regression | 0.6419 | 0.2999 | 0.1660 | Baseline Model |
| **Ridge (L2)** | **0.6419 / CV ≈ 0.695** | **0.2998** | **0.1661** | Best Stability + Generalization |
| Lasso (L1)** | 0.6384 | 0.3004 | 0.1740 | Slight Underfit |

#### 🔍 **Key Insights**
- **Hospitalised → Negative impact**, indicating higher survival.  
- **Method_Pesticide & Occupation_Farming → Positive relation** with fatalities.  
- **Age & Year → Temporal trend**, showing increased risk among older groups.

---

### 🤖 **Reinforcement Learning — Conceptual Perspective**

Although not implemented, **Reinforcement Learning (RL)** was studied conceptually for dynamic suicide prevention policy modeling.

| Aspect | Supervised Learning | Reinforcement Learning |
|:--|:--|:--|
| **Input Data** | Labeled samples | Reward feedback from environment |
| **Goal** | Minimize prediction error | Maximize cumulative reward |
| **Example** | Predict suicide fatality | Simulate policy to reduce fatalities |
| **Feedback** | Immediate and direct | Delayed and cumulative |

**Applications:** Healthcare optimization · Resource allocation · Adaptive policy formulation · Mental health intervention design  

---

### 📊 **Key Findings Across Phases**

- Suicide fatalities correlate strongly with **occupation (farming)** and **method (pesticide)**.  
- **Hospitalisation** acts as a major protective variable.  
- **Dimensionality Reduction** uncovered two latent components — demographic and method-based.  
- **Ridge Regression** achieved the best balance of bias and variance.  
- Conceptually, **Reinforcement Learning** provides a framework for adaptive intervention policy design.

---

### 🧩 **Future Scope**

- Extend to **classification models** (Logistic Regression, Random Forest, XGBoost).  
- Integrate **psychological, healthcare, and economic datasets** for holistic insights.  
- Implement **time-series forecasting** to predict long-term suicide trends.  
- Apply **SHAP-based explainability** for transparent and ethical model interpretation.  

---

✅ **Ready for Evaluation:** Phase 1 + Phase 2 + Phase 3 tasks completed, results documented, and notebook committed to GitHub.  


---

## 🏁 **Project Status**

| Phase | Description | Status |
|:--|:--|:--:|
| **Phase 1** | Data Cleaning & Multivariate EDA | ✅ Completed |
| **Phase 2** | Advanced EDA & Clustering | ✅ Completed |
| **Phase 3** | Dimensionality Reduction & Modeling | ✅ Completed |
| **Final Report** | Documentation & VTop Submission | 🟢 Ready |

---

## 📬 Contact

For queries related to this project:  
📧 Email: [parthsuri009@gmail.com](mailto:parthsuri009@gmail.com)  
📌 GitHub: [https://github.com/PSURI1894](https://github.com/PSURI1894)

---

> _This project is a part of academic coursework at Vellore Institute of Technology (VIT), and all rights are reserved for educational use only._

