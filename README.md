# Capstone Projects Documents for Mass PRIM Internship Application

Thank you for considering my application for the internship at Massachusetts Pension Reserves Investment Management (Mass PRIM). This repository contains summaries of two capstone projects I completed, which demonstrate my analytical and quantitative skills in handling time series data, dimensionality reduction, and outlier detection.

---

## Table of Contents
1. [Overview](#overview)  
2. [Project 1: Time Series Data Dimensionality Reduction (with ASK2.ai)](#project-1-time-series-data-dimensionality-reduction-with-ask2ai)  
3. [Project 2: Outlier Detection System (with Wellington Management)](#project-2-outlier-detection-system-with-wellington-management)  
4. [Contents of This Repository](#contents-of-this-repository)  
5. [Acknowledgments](#acknowledgments)

---

## Overview
This repository serves as a concise showcase of my work for two separate capstone projects:

1. **Time Series Data Dimensionality Reduction** (in collaboration with ASK2.ai), where I explored multiple dimensionality reduction techniques—specifically **t-SNE** and **UMAP**—applied to mutual fund data.  
2. **Outlier Detection System** (in collaboration with Wellington Management), focusing on detecting anomalous transaction volumes across 50 companies over six years of data using various time-series and statistical methods.

To keep the documentation succinct, I have included only a poster and a brief report for each project, highlighting the key findings and methodologies.

---

## Project 1: Time Series Data Dimensionality Reduction (with ASK2.ai)

### Background
- **Goal**: Reduce the dimensionality of large mutual fund datasets to gain deeper insights and visualize inherent structures more effectively.
- **Techniques Used**: 
  - [t-SNE](https://lvdmaaten.github.io/tsne/): A non-linear dimensionality reduction method effective for visualizing high-dimensional data in a lower-dimensional space.
  - [UMAP](https://umap-learn.readthedocs.io/en/latest/): A novel technique that preserves both local and global data structure effectively.
  - Compared these two methods against the conventional **PCA** approach.

### Key Contributions
- **Rolling Robust Method**: Implemented a rolling robust estimation technique to address **inconsistency** in time-series data, ensuring stable dimensionality reduction over time.
- **Advantages Over PCA**: Demonstrated how t-SNE and UMAP could capture non-linear relationships and reveal cluster structures that standard PCA might miss.

### Outcomes
- Gained a clearer understanding of mutual fund data clusters and anomalies.
- Established a reproducible workflow for applying rolling robust approaches in dimensionality reduction tasks.

---

## Project 2: Outlier Detection System (with Wellington Management)

### Background
- **Goal**: Identify transaction volume anomalies for 50 companies over a 6-year time span.
- **Challenge**: Large, noisy time-series data requiring robust anomaly detection methods.

### Methods Employed
- **Eight Outlier Detection Approaches**:  
  - Time-series based (e.g., ARIMA residual analysis, rolling Z-scores)  
  - Statistical methods (e.g., Tukey’s fences, robust standard deviations)  
- These eight approaches were combined through a **deep learning voting system**, trained to give a final verdict on whether a data point is an outlier.

### Key Contributions
- Developed a comprehensive framework to detect anomalies by **aggregating** multiple detection methods.
- Showed improved accuracy and reduced false positives through the ensemble (voting) approach.

### Outcomes
- A robust outlier detection pipeline that can scale to diverse financial datasets.
- Insights into how combining different detection methodologies can improve performance over single-method approaches.

---

## Contents of This Repository

- **`TimeSeries_DimensionalityReduction_Poster.pdf`**  
  A concise visual summary of the t-SNE, UMAP, and PCA comparison project, along with the rolling robust method.

- **`TimeSeries_DimensionalityReduction_Report.pdf`**  
  A brief written report detailing the methodology and results of the dimensionality reduction project.

- **`OutlierDetectionSystem_Poster.pdf`**  
  A high-level overview of the outlier detection framework, showcasing the eight methods and how the voting system is constructed.

- **`OutlierDetectionSystem_Report.pdf`**  
  A short report explaining the experimental setup, data sources, and key findings from the anomaly detection project.

*(Note: The full codebase and comprehensive datasets are not included here to avoid an overly lengthy repository. Please contact me if more details or additional documentation are needed.)*

---

## Acknowledgments
I would like to extend my sincere gratitude to **Massachusetts Pension Reserves Investment Management (Mass PRIM)** for the opportunity to share these projects as part of my internship application. Special thanks to:
- **ASK2.ai** for the collaboration and support during the dimensionality reduction project.  
- **Wellington Management** for providing guidance and resources for the outlier detection system.

These experiences have been instrumental in refining my technical and analytical skills, and I look forward to the possibility of contributing further at Mass PRIM.

---

Thank you for reviewing my projects! If you have any questions or need more information, please let me know.
