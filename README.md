# Prozorro: Anomaly Detection in Procurement Data

This repository contains the final project for the Machine Learning course, focused on detecting anomalies in Ukrainian public procurement data using various unsupervised learning techniques.

## 🧑‍🏫 Authors

- Khrystyna Mysak
- Bohdan Pavliuk

---

## 📦 Project Pipeline

1. **Data Collection**  
   Gathered procurement data from the Dozorro database.

2. **Data Preparation**  
   Cleaned and preprocessed the raw data for analysis.

3. **Exploratory Data Analysis (EDA)**  
   Visualized key trends, distributions, and patterns in the data.

4. **Modeling**  
   Applied several unsupervised algorithms to detect anomalies.

---

## 📊 Dataset

The data is sourced from the [Dozorro Tenders Database](https://bi.prozorro.org/hub/stream/aaec8d41-5201-43ab-809f-3063750dfafd), covering the years **2015–2025** (up to early 2025).

📁 [Download full CSV file](https://drive.google.com/file/d/1I8AY3x8bb6bSPLJwSjywTqagXSw8MGlO/view?usp=sharing)

---

## 🧠 Modeling Approaches

We experimented with a variety of anomaly detection methods:

- **KMeans Clustering**
- **DBSCAN (Density-Based Spatial Clustering)**
- **Autoencoder (Neural Network)**
- **Isolation Forest**

---

## 📁 Repository Structure

| File | Description |
|------|-------------|
| `EDA&Preparation.ipynb` | Data cleaning and exploratory analysis |
| `Prozorro_KMeans_DBSCAN.ipynb` | Implementation using KMeans and DBSCAN |
| `Prozorro_AE.ipynb` | Autoencoder-based anomaly detection |
| `Isolated_forest.ipynb` | Isolation Forest model implementation |

---

## 📌 Notes

- This project focuses on unsupervised learning approaches.
- Anomalies may signal potential irregularities or suspicious procurement behavior.

---
