# IPL Player Performance Analysis

![License](https://img.shields.io/badge/license-MIT-green)
![Python](https://img.shields.io/badge/python-3.8+-blue)
![Status](https://img.shields.io/badge/status-Active-brightgreen)

This repository contains the code and analysis from the research paper titled:

📄 **"A Methodological Approach Utilising Factor Analysis and Clustering to Evaluate the Strengths and Weaknesses of IPL Players"**  
🔗 Published in *Indian Journal of Science and Technology*  
📚 [Read the full paper here](https://indjst.org/articles/a-methodological-approach-utilising-factor-analysis-and-clustering-to-evaluate-the-strengths-and-weaknesses-of-ipl-players)

---

## 📊 Dataset

The dataset used for this study is sourced from Kaggle:

- 🗂 **IPL 2022 Match Dataset**  
- 🔗 [Kaggle Dataset Link](https://www.kaggle.com/datasets/vora1011/ipl-2022-match-dataset)

It contains detailed match-level and player-level statistics for IPL 2022 including:

- Batting and bowling statistics
- Match-level data
- Player performance per match

---

## 📌 Objective

To evaluate the **strengths and weaknesses** of IPL players using:

- **Factor Analysis** to reduce dimensionality and extract latent performance factors.
- **Clustering Techniques** (like K-Means and Hierarchical Clustering) to segment players into meaningful performance groups.
- **Visualization** and **insights** to support franchise strategy, player selection, and performance improvement.

---

## 🧠 Methodology

### 🔍 1. Data Preprocessing
- Cleaned missing and irrelevant values
- Normalized statistical features
- Created derived metrics (e.g., strike rate, economy rate)

### 🧪 2. Factor Analysis
- Reduced high-dimensional feature space into interpretable components (e.g., aggressive batting, efficient bowling)

### 🔗 3. Clustering
- Applied K-Means and Hierarchical Clustering
- Visualized clusters to interpret player types (e.g., Finishers, Anchors, Death Bowlers)

### 📊 4. Visualization & Interpretation
- Used seaborn, matplotlib for visual clusters
- Radar plots and heatmaps for player profiles

---
