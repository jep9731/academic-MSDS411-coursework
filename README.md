# 🔍 MSDS 411: Unsupervised Learning Methods

![Course](https://img.shields.io/badge/Course-MSDS%20411-blue)
![Type](https://img.shields.io/badge/Type-Project--Based-brightgreen)
![Language](https://img.shields.io/badge/Language-R-yellow)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

> **Master of Science in Data Science — Unsupervised Learning Methods**
> 
> A project-based course exploring traditional and modern unsupervised learning techniques for dimensionality reduction, clustering, anomaly detection, and multivariate data visualization.

---

## 📌 Course Overview

This course introduces a broad range of unsupervised learning methods applied to real-world datasets through extensive programming assignments and projects. Unlike supervised learning, unsupervised methods uncover hidden structure in data without labeled responses — making them essential tools for exploratory analysis, pattern recognition, and anomaly detection.

---

## 🧠 Topics Covered

### 📐 Dimensionality Reduction
- **Principal Component Analysis (PCA)** — Represent relationships among many continuous variables by reducing to orthogonal components
- **Factor Analysis** — Model latent structure underlying observed variables

### 👥 Clustering
- **Cluster Analysis** — Identify natural groupings of individuals within data
- **Block Clustering** — Simultaneously cluster rows and columns (biclustering) to identify groups of variables

### 📊 Categorical Variable Analysis
- **Log-Linear Models** — Explore relationships and dependencies among categorical variables
- **Association Rules** — Mine frequent patterns and co-occurrence rules (e.g., Apriori, FP-Growth)

### 🎨 Multivariate Visualization
- **Lattice Displays** — Visualize conditional relationships across multiple variables
- **Multidimensional Scaling (MDS)** — Embed high-dimensional data into lower-dimensional space preserving distances
- **t-SNE** — t-Distributed Stochastic Neighbor Embedding for non-linear dimensionality reduction and visualization

### 🚨 Anomaly Detection
- **Autoencoders** — Detect anomalies by measuring reconstruction error from neural network encoders
- **Probabilistic Deep Learning** — Model uncertainty and detect outliers using probabilistic approaches

---

## 🗂️ Repository Structure

```
📦 msds411-unsupervised-learning/
├── 📁 assignments/
│   ├── assignment_01_pca/
│   ├── assignment_02_factor_analysis/
│   ├── assignment_03_clustering/
│   ├── assignment_04_block_clustering/
│   ├── assignment_05_log_linear_models/
│   ├── assignment_06_association_rules/
│   ├── assignment_07_visualization/
│   └── assignment_08_anomaly_detection/
├── 📁 data/
│   ├── raw/
│   └── processed/
├── requirements.txt
└── README.md
```

---

## 🛠️ Tech Stack

| Category | Tools |
|---|---|
| **Language** | R 4.3+ |
| **Core Libraries** | tidyverse, data.table, matrixStats |
| **Machine Learning** | caret, tidymodels, cluster, factoextra |
| **Association Rules** | arules, arulesViz |
| **Deep Learning** | keras, tensorflow |
| **Visualization** | ggplot2, lattice, plotly, ggfortify |
| **Dimensionality Reduction** |stats, Rtsne, umap, factoextra |
| **Notebooks** | R Markdown, Quarto |
| **Environment Management** | renv |

---

## ⚙️ Getting Started

### Prerequisites

- R 4.3+
- RStudio (recommended)
- Git

---

### Installation
#### Clone the Repository
```bash
# Clone the repository
git clone https://github.com/jep9731/academic-MSDS411-coursework.git
cd academic-MSDS411-coursework
```

#### Restore R Environment
```bash
# Create and activate environment
install.packages("renv")
renv::restore()
```

#### Install Required Packages Manually (Optional)

```bash
install.packages(c(
  "tidyverse",
  "data.table",
  "cluster",
  "factoextra",
  "caret",
  "tidymodels",
  "arules",
  "arulesViz",
  "Rtsne",
  "umap",
  "keras",
  "tensorflow",
  "plotly",
  "lattice"
))
```

---

## 📋 Assignments & Projects

| # | Topic | Methods |
|---|---|---|
| 1 | Dimensionality Reduction | PCA |
| 2 | Latent Structure | Factor Analysis |
| 3 | Grouping Individuals | Cluster Analysis (K-Means, Hierarchical) |
| 4 | Grouping Variables | Block Clustering / Biclustering |
| 5 | Categorical Relationships | Log-Linear Models |
| 6 | Pattern Mining | Association Rules |
| 7 | Multivariate Visualization | Lattice, MDS, t-SNE |
| 8 | Anomaly Detection | Autoencoders, Probabilistic Deep Learning |
| — | **Final Project** | End-to-end unsupervised analysis |

---

## 🎯 Learning Objectives

By the end of this course, students are able to:

- Apply dimensionality reduction techniques to continuous multivariate data
- Identify and interpret natural groupings using a variety of clustering methods
- Mine association rules and model dependencies in categorical data
- Visualize high-dimensional data using scaling and embedding techniques
- Build and deploy autoencoder-based anomaly detection systems
- Communicate unsupervised learning findings clearly to technical and non-technical audiences

---

## 📬 Contact

For questions related to coursework or collaboration, reach out via GitHub Issues or the contact information below.

| | |
|---|---|
| **Student** | `Joshua Pasaye` |
| **Email** | `joshuapasaye2027@u.northwestern.edu` |
| **Program** | Master of Science in Data Science |
| **Course** | MSDS 411 — Unsupervised Learning Methods |

---

*This repository contains coursework completed as part of the MSDS 411-DL: Unsupervised Learning Methods course in the Master of Science in Data Science program.*
