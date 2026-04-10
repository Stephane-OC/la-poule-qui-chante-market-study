# 🐔 La poule qui chante — International Market Study for Poultry Export

Welcome to the **La poule qui chante Market Study Project**, a data analysis project designed to support an international expansion strategy for a fictional poultry company.

This repository contains the full analytical workflow used to identify **groups of countries that could be targeted for chicken exports**, using open data and multivariate analysis.

The project was developed with a strong focus on:

- **clarity**
- **reproducibility**
- **business relevance**
- and **decision-making support for non-technical stakeholders**

---

## 🚀 Live Access

📘 **Notebook 1 — Data Preparation, Cleaning & EDA**  
➡️ [Open the HTML version](https://stephane-oc.github.io/la-poule-qui-chante-market-study/)

📊 **Notebook 2 — PCA, Clustering & Recommendations**  
➡️ [Open the clustering HTML version](https://stephane-oc.github.io/la-poule-qui-chante-market-study/clustering.html)

💻 **Jupyter Notebook Files**
- [preparation_nettoyage_EDA.ipynb](./preparation_nettoyage_EDA.ipynb)
- [ACP_clustering.ipynb](./ACP_clustering.ipynb)

---

## 📌 Project Overview

**La poule qui chante** wants to expand internationally and needs a first-level market screening to determine which groups of countries should be prioritized for poultry export development.

Rather than conducting a full country-by-country market study from the start, the goal of this project is to:

- compare countries using relevant food, demographic, and economic indicators,
- identify **homogeneous country groups**,
- and provide **strategic recommendations** for future market prioritization.

This project is divided into **two complementary notebooks**.

---

## 📂 Repository Content

### 1. `preparation_nettoyage_EDA.ipynb`
This notebook covers:

- data import and initial understanding
- variable selection
- data cleaning and transformation
- dataset construction at country level
- feature engineering
- exploratory data analysis

Its purpose is to create a **clean, structured, and analysis-ready dataset** for the second notebook.

---

### 2. `ACP_clustering.ipynb`
This notebook covers:

- data standardization
- Principal Component Analysis (PCA)
- explained variance analysis
- correlation circle
- projection of individuals
- hierarchical clustering
- K-means clustering
- cluster profiling
- business recommendations for the executive committee

Its purpose is to turn the prepared dataset into **actionable strategic insights**.

---

## 🎯 Main Objectives

The project aims to answer the following business question:

> **Which country groups should La poule qui chante prioritize for poultry export expansion?**

To answer this, the analysis focuses on:

- food availability indicators
- poultry-related variables
- demographic structure
- derived market indicators
- multivariate analysis and country segmentation

---

## 🧩 Key Features

- 🌍 Country-level international data analysis
- 🧹 Structured data cleaning and preparation workflow
- 🛠️ Feature engineering with derived variables
- 📊 Exploratory data analysis with business interpretation
- 📉 Principal Component Analysis (PCA)
- 🌳 Hierarchical clustering (CAH)
- 🎯 K-means clustering
- 📣 Executive-oriented recommendations

---

## 🧠 Analytical Workflow

### Notebook 1 — Data Preparation, Cleaning & EDA

- Import libraries and source files
- Understand the project scope and business problem
- Explore source datasets
- Select the most relevant variables
- Clean and reshape the data
- Merge datasets at country level
- Create derived variables
- Perform exploratory analysis
- Produce the final dataset for PCA and clustering

### Notebook 2 — PCA, Clustering & Strategic Recommendations

- Load the final dataset
- Standardize numerical variables
- Run PCA
- Analyze explained variance
- Build the correlation circle
- Project countries onto factorial planes
- Perform hierarchical clustering
- Run K-means clustering
- Compare segmentation methods
- Interpret clusters
- Recommend target country groups for the COMEX

---

## 🗂️ HTML Navigation

This repository also includes HTML exports of both notebooks:

- `index.html` → HTML version of **Notebook 1**
- `clustering.html` → HTML version of **Notebook 2**

The main HTML page can include a direct navigation link or button to the clustering page for easier browsing through GitHub Pages.

---

## 🧪 Technical Stack

| Category | Tools & Libraries |
|----------|-------------------|
| **Language** | Python |
| **Data Analysis** | pandas, numpy |
| **Visualization** | matplotlib, seaborn |
| **Scientific Computing** | scipy |
| **Environment** | Jupyter Notebook |
| **Data Sources** | FAO, open data sources |