# 🛒 E-commerce Customer Behavior Analysis

This project focuses on analyzing customer behavior using an online retail dataset. It uses **Cohort Analysis** and **RFM Segmentation** to uncover insights about customer retention and purchasing patterns.

---

## 📌 Project Goals

- Understand customer purchasing behavior.
- Identify loyal vs. one-time customers.
- Segment customers based on **Recency**, **Frequency**, and **Monetary Value**.
- Perform **Cohort Analysis** to track customer retention over time.

---

## 📊 Dataset

We used the **Online Retail** dataset from the UCI Machine Learning Repository.

- **Link**: [Download Dataset](https://archive.ics.uci.edu/ml/machine-learning-databases/00352/Online%20Retail.xlsx)
- **Size**: ~22MB
- **Note**: The dataset is not included in this repository due to size constraints. Please download it manually from the above link and place it in the project directory.

---

## 🧼 Data Cleaning

- Removed rows with missing `CustomerID`.
- Dropped rows with missing `Description`.
- Removed negative or zero values from `Quantity` and `UnitPrice`.
- Added a new column: `TotalPrice = Quantity * UnitPrice`

---

## 🗓️ Cohort Analysis

- Extracted **Invoice Month** and **Cohort Month**.
- Calculated **Cohort Index** to measure customer retention across months.
- Created a **Cohort Matrix** to visualize retention patterns.

---

## 📦 RFM Segmentation

RFM = Recency, Frequency, Monetary

- **Recency**: Days since the last purchase.
- **Frequency**: Number of purchases.
- **Monetary**: Total spend by the customer.

Segmented customers into groups using quantiles for better marketing and targeting strategies.

---

## 🧰 Tools Used

- Python 🐍
- Pandas 📊
- Matplotlib & Seaborn 📈
- Jupyter Notebook 📒

---

## 📁 Project Structure

