# TD – Clustering (K-Means & Hierarchical)

## Overview
This repository contains the work for the **Clustering TD** from the Data Science course at **INSA Centre-Val de Loire**.  
The goal is to apply unsupervised learning methods (**K-Means** and **Hierarchical Clustering**) to socio-economic data of 167 countries, using **PCA** for dimensionality reduction and visualization.

---

## Files
TD_Clustering/
- ┣ 📜 CHICA-Miller_TORRES-Jonathan_TD_Clustering.ipynb
- ┣ 📜 Country-data.csv
- ┗ 📜 README.md
- `CHICA-Miller_TORRES-Jonathan_TD_Clustering.ipynb` → main notebook (code + analysis)  
- `Country-data.csv` → dataset used for clustering  
- `README.md` → project summary  

---

## Requirements
Install the required libraries:

```bash
pip install numpy pandas matplotlib scipy scikit-learn
```
---

## Summary

PCA: reduces 9 variables to 2 main components for visualization.

K-Means (k=2, k=3): distinguishes developed, developing, and emerging countries.

Hierarchical clustering (single & complete link): confirms similar global patterns with more gradual grouping.

---

## Authors

Miller Chica

Jonathan Torres

INSA Centre-Val de Loire – STI Department
Academic Year 2024–2025
