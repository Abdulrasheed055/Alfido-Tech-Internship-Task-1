# Alfido-Tech-Internship-Task-1

## 📌 Project Overview

This project focuses on **customer segmentation** using **K-Means clustering**. The goal is to group customers into meaningful segments based on their behavior and characteristics, enabling businesses to **target the right customers with personalized strategies**.

The project was completed as part of my **Business Analysis Internship at Alfido Tech**.

---

## 🎯 Objectives

* Clean and preprocess the dataset
* Apply **K-Means clustering** to segment customers
* Evaluate clustering performance
* Visualize clusters for interpretation
* Build **customer personas (Cluster A–C)** for better business insights

---

## 📂 Dataset

* The dataset contains customer attributes such as **age, income, family size, and spending habits**.
* After preprocessing, the features were used as input for clustering.

---

## 🛠️ Methodology

1. **Data Preprocessing**

   * Checked for missing values and outliers
   * Normalized features for fair clustering

2. **K-Means Clustering**

   * Chose number of clusters using **Elbow Method & Silhouette Score**
   * Optimal number of clusters found: **3**

3. **Evaluation**

   * Clustering performance assessed using:

     * **Silhouette Score**
     * **Davies-Bouldin Index**
     * **F1-macro (cross-validation for downstream classification)**

4. **Visualization**

   * 2D scatter plots of clusters
   * Heatmaps to compare cluster means
   * Tables summarizing segment characteristics

---

## 📊 Results

### Cluster Summary (0–4 Clusters Example)

| Cluster | Age Group           | Income Level | Spending Score | Family Size    | Insight              |
| ------- | ------------------- | ------------ | -------------- | -------------- | -------------------- |
| 0       | Young Adults        | Low          | Low            | Large Families | Budget-conscious     |
| 1       | Middle-Aged         | Medium       | Medium         | Small          | Balanced group       |
| 2       | Seniors             | High         | High           | Medium         | High-value customers |
| 3       | Adults              | Medium       | Low            | Large          | Price-sensitive      |
| 4       | Young Professionals | High         | Medium         | Small          | Growth segment       |

---

### Customer Personas (A–C Mapping)

| Persona                          | Key Traits                                          | Business Implication                          |
| -------------------------------- | --------------------------------------------------- | --------------------------------------------- |
| **A: Budget-Conscious Families** | Younger, larger households, lower income & spending | Target with **discounts & family packages**   |
| **B: Balanced Shoppers**         | Middle-aged, average income, steady spending        | Maintain engagement with **loyalty programs** |
| **C: High-Value Customers**      | Seniors/professionals, high income & spending       | Focus on **premium offers & retention**       |

---

## 📈 Visualizations

* **Cluster Scatter Plot** (Age vs. Spending Score)
* **Bar Charts** showing average income & spending per cluster
* **Heatmap** comparing cluster characteristics

*(Insert your plots here in the repo as PNGs or directly in the notebook)*

---

## 📌 Key Insights

* Younger families spend less → need targeted discounts
* Middle-aged balanced customers → sustain loyalty with engagement programs
* High-income customers → opportunity for premium services

---


Would you like me to also **write the code template (Python notebook structure)** that fits into this GitHub repo so you can just drop in your dataset and run everything smoothly?
