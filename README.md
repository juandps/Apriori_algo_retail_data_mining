# Apriori Algorithm Implementation in Retail Data Mining

## 📌 Overview
This project implements **association rule mining** using the **Apriori Algorithm**, **Brute-Force**, and **FP-Growth** techniques. It provides a **Flask-based web application** for analyzing **transactional data** from major retailers (Amazon, Best Buy, K-Mart, Nike, and a generic dataset). Users can select datasets, set **minimum support and confidence**, and visualize the generated **association rules**.

## 🚀 Features
- **Association Rule Mining** using:
  - **Brute-Force**
  - **Apriori Algorithm**
  - **FP-Growth Algorithm**
- **Flask-based Web Interface**
- **Dataset Selection**
- **Performance Comparison** between algorithms
- **Result Visualization** with frequent itemsets and association rules

## 📊 Core Concepts
### 🔹 Frequent Itemset Discovery
Identifies **items that appear together frequently** in transactions.

### 🔹 Support & Confidence
- **Support:** Frequency of an itemset in the dataset.
- **Confidence:** Probability of item B appearing given item A.

### 🔹 Association Rules
Generated in the form: **{A} → {B}**, meaning **if A is bought, B is likely to be bought**.

## 🏗️ Project Workflow
1. **Data Loading** – Load transactional datasets.
2. **Preprocessing** – Encode data for analysis.
3. **Parameter Selection** – Users set **support** & **confidence** thresholds.
4. **Algorithm Execution** – Run **Brute-Force, Apriori, or FP-Growth**.
5. **Result Comparison** – Compare performance across algorithms.
6. **Visualization** – Display results in the web interface.

## 🛠️ Installation & Setup
### 🔹 Dependencies
Install required Python packages:
```sh
pip install Flask pyngrok mlxtend apriori_python
