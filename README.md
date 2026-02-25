# 📊 Poverty Inequality Analysis in Central Java
## Agglomerative Hierarchical Clustering (AHC)

---

## 📌 Overview

This project analyzes poverty inequality across districts and municipalities in Central Java Province using **Agglomerative Hierarchical Clustering (AHC)**.

The objective is to group regions based on multidimensional poverty indicators to identify areas that require priority intervention.

Central Java is one of the provinces with high poverty levels in Java and has one of the lowest Provincial Minimum Wages (UMP) in Indonesia (IDR 1,958,169 in 2023). Understanding poverty distribution at the district level is essential for targeted policy-making.

---

## 🎯 Objective

To classify districts/municipalities in Central Java into homogeneous groups based on poverty-related indicators using hierarchical clustering techniques.

---

## 📊 Data Description

Unit of analysis:
- Districts/Municipalities in Central Java

### Poverty and Socioeconomic Indicators

| Indicator | Description |
|------------|------------|
| GK | Poverty Line |
| PPM | Percentage of Poor Population |
| P1 | Poverty Gap Index |
| P2 | Poverty Severity Index |
| Expenditure Distribution (Bottom 40%) | World Bank Criteria |
| Unemployment | Number of unemployed individuals |
| RLS | Average Years of Schooling |
| HLS | Expected Years of Schooling |

These indicators represent multidimensional aspects of poverty including income, inequality, education, and employment.

---

## 🧠 Methodology

### 1️⃣ Data Preprocessing
- Data cleaning
- Standardization of variables
- Multivariate distance calculation

### 2️⃣ Clustering Method

Agglomerative Hierarchical Clustering (AHC) was applied using three linkage methods:

- Single Linkage
- Complete Linkage
- Average Linkage

Clustering process:
- Each region starts as its own cluster
- Clusters are merged iteratively based on similarity
- Dendrogram used to determine optimal number of clusters

---

## 📈 Results

The analysis identified **two distinct clusters**:

- **Cluster 1 (High Poverty Level)**  
  - 31 districts/municipalities

- **Cluster 2 (Low Poverty Level)**  
  - 4 municipalities

This indicates a strong structural inequality pattern across regions.

---

## 🔎 Interpretation

Regions in Cluster 1 exhibit:

- Higher poverty rates
- Higher unemployment
- Lower education levels
- Greater poverty severity

Cluster 2 consists mainly of urban municipalities with relatively better socio-economic conditions.

---

## 🏛 Policy Implications

To reduce poverty in Cluster 1, policy recommendations include:

- Expansion of social welfare programs
- Improvement of educational facilities
- Job creation and vocational training
- Strengthening human capital development

Targeted intervention based on cluster characteristics allows more efficient policy allocation.

---

## 🛠 Tool
R
