# 🐔 La poule qui chante • International Market Study for Poultry Export

Welcome to the **La poule qui chante Market Study Project**, a data analysis project designed to support an international expansion strategy for a fictional poultry company.

This repository contains the full analytical workflow used to identify **groups of countries that could be targeted for chicken exports**, using open data and multivariate analysis.

The project was developed with a strong focus on:

- clarity
- reproducibility
- business relevance
- decision-making support for non-technical stakeholders

---

## 🚀 Live Access

📘 **Notebook 1 • Data Preparation, Cleaning & EDA**  
➡️ [Open the HTML version](https://stephane-oc.github.io/la-poule-qui-chante-market-study/)

📊 **Notebook 2 • PCA, Clustering & Recommendations**  
➡️ [Open the clustering HTML version](https://stephane-oc.github.io/la-poule-qui-chante-market-study/clustering.html)

📄 **Final Presentation • PDF version**  
➡️ [Open the presentation PDF](./docs/la_poule_qui_chante_market_study_presentation.pdf)

💻 **Jupyter Notebook Files**

- [preparation_nettoyage_EDA.ipynb](./preparation_nettoyage_EDA.ipynb)
- [ACP_clustering.ipynb](./ACP_clustering.ipynb)

---

## 📌 Project Overview

**La poule qui chante** wants to expand internationally and needs a first-level market screening to determine which groups of countries should be prioritized for poultry export development.

Rather than conducting a full country-by-country market study from the start, the goal of this project is to:

- compare countries using relevant food, demographic, economic, commercial and political indicators
- identify **homogeneous country groups**
- build a first prioritization of promising markets
- provide **strategic recommendations** for future market studies and COMEX decision-making

This project is divided into **two complementary notebooks** and a final presentation.

---

## 📂 Repository Content

### 1. `preparation_nettoyage_EDA.ipynb`

This notebook covers:

- data import and initial understanding
- variable selection
- data cleaning and transformation
- country perimeter cleaning
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
- projection of countries on factorial planes
- hierarchical clustering
- K-means clustering
- comparison between clustering methods
- cluster profiling
- attractiveness scoring
- business recommendations for the executive committee

Its purpose is to turn the prepared dataset into **actionable strategic insights**.

---

### 3. `docs/la_poule_qui_chante_market_study_presentation.pdf`

This PDF contains the final presentation used to communicate:

- the business context
- the data preparation process
- the PCA results
- the clustering methodology
- the cluster interpretation
- the COMEX-oriented recommendations
- the Data Analyst skills mobilized during the project

---

## 📦 Final Deliverables

- Data preparation and EDA notebook
- PCA and clustering notebook
- HTML exports for both notebooks
- Final presentation in PDF format
- Clean country-level dataset used for multivariate analysis
- Strategic recommendation for country group prioritization

---

## 🎯 Main Objective

The project aims to answer the following business question:

> **Which country groups should La poule qui chante prioritize for poultry export expansion?**

To answer this, the analysis focuses on:

- food availability indicators
- poultry-related trade and production variables
- population and demographic structure
- economic and political indicators
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
- 🔍 Comparison between clustering approaches
- 📌 Cluster profiling and attractiveness scoring
- 📣 Executive-oriented recommendations

---

## 🧠 Analytical Workflow

### Notebook 1 • Data Preparation, Cleaning & EDA

- Import libraries and source files
- Understand the project scope and business problem
- Explore source datasets
- Select the most relevant variables
- Clean and reshape the data
- Harmonize country names and country perimeter
- Merge datasets at country level
- Add economic and political indicators
- Create derived variables
- Perform exploratory analysis
- Produce the final dataset for PCA and clustering

### Notebook 2 • PCA, Clustering & Strategic Recommendations

- Load the final dataset
- Standardize numerical variables
- Run PCA
- Analyze explained variance
- Select the number of retained PCA axes
- Build the correlation circle
- Project countries onto factorial planes
- Perform hierarchical clustering
- Choose a coherent number of clusters
- Run K-means clustering
- Compare hierarchical clustering and K-means results
- Interpret cluster profiles using business variables
- Build an attractiveness score
- Recommend priority country groups for the COMEX

---

## 🗂️ HTML Navigation

This repository includes HTML exports of both notebooks:

- `index.html` • HTML version of **Notebook 1**
- `clustering.html` • HTML version of **Notebook 2**

The HTML exports allow the analysis to be reviewed without opening the Jupyter notebooks directly.

---

## 🧪 Technical Stack

| Category | Tools & Libraries |
|----------|-------------------|
| **Language** | Python |
| **Data Analysis** | pandas, numpy |
| **Visualization** | matplotlib, seaborn |
| **Scientific Computing** | scipy |
| **Machine Learning / Statistics** | scikit-learn |
| **Environment** | Jupyter Notebook |
| **Data Sources** | FAO, World Bank, open data sources |

---

## 📊 Main Methodological Choices

The analysis uses PCA and clustering to simplify and structure the dataset before making recommendations.

### PCA

Principal Component Analysis was used to reduce the complexity of the dataset while keeping most of the information.

The retained PCA axes summarize the main differences between countries and provide a compact basis for the clustering steps.

### Hierarchical Clustering

Hierarchical clustering was used to explore the natural structure of the data and guide the choice of a relevant number of country groups.

The dendrogram helped identify a coherent segmentation into four groups.

### K-means Clustering

K-means was then used to produce the final segmentation.

The chosen number of clusters was kept consistent with the hierarchical clustering analysis in order to obtain a stable, readable and business-oriented classification.

---

## 🏆 Main Recommendation

The analysis identifies **Cluster 2** as the priority group for further market studies.

This cluster contains countries with strong economic and commercial profiles, significant import volumes and promising market potential.

**Cluster 4** is recommended as a secondary group to monitor and study further, as it includes a wider set of stable and economically favorable markets.

The recommendation is not to enter all these markets immediately, but to use the segmentation as a **first decision-support tool** before conducting detailed country-by-country studies.

---

## ⚠️ Limitations

This analysis is based on data from 2017 and should be considered as a first screening step.

Before any operational market entry decision, the results should be updated and completed with recent information on:

- current poultry market trends
- sanitary and regulatory barriers
- logistics costs
- local competition
- geopolitical context
- consumer demand
- trade agreements and import restrictions

The clustering and attractiveness score are decision-support tools. They do not replace a full market study.

---

## 📣 Business Value

This project helps transform a complex international dataset into a readable strategic recommendation.

It provides:

- a cleaner understanding of country profiles
- a first prioritization of promising markets
- a structured basis for COMEX discussions
- a reproducible analytical workflow
- a bridge between statistical analysis and business decision-making

---