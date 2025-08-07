# Task 3 – RFM Customer Segmentation

## 📌 Objective

The goal of this task was to apply RFM analysis (Recency, Frequency, Monetary) on a real-world ecommerce dataset to segment customers based on their purchasing behavior and value to the business.

---

## 🧰 Tools & Libraries Used

- Python (Pandas, NumPy)
- Seaborn, Matplotlib
- Google Colab
- Dataset: Online Retail.xlsx (UCI Machine Learning Repository)

---

## 🧹 Data Cleaning Summary

The dataset was cleaned before analysis using the following steps:

- Removed rows with missing CustomerIDs
- Removed canceled transactions (InvoiceNo starting with "C")
- Removed negative or zero quantities
- Converted InvoiceDate to datetime
- Created a new column: `TotalPrice = Quantity × UnitPrice`

---

## 📊 RFM Calculation

For each customer, we calculated:

- 📅 Recency: Days since last purchase  
- 🔁 Frequency: Number of unique invoices  
- 💰 Monetary: Total spending across all purchases

A reference date was set as one day after the last transaction in the dataset.

RFM scores (1–5) were then assigned using quintiles, and each customer was given an RFM segment (e.g., “453”) and total RFM score (sum of all three scores).

---

## 🧱 Customer Segmentation

Customers were grouped based on their RFM score:

| Segment     | Description                          |
|-------------|--------------------------------------|
| Champions   | Most recent, frequent, high-spending |
| Loyal       | Frequent buyers                      |
| At Risk     | Haven’t purchased in a while         |
| Lost        | Inactive, low-value customers        |

---

## 📊 Visualizations

The following visualizations were created:

- Bar chart of customer count per segment
- Heatmap of average monetary value by Recency and Frequency scores

---

## 🎯 Outcome

RFM segmentation helps identify which customers to:

- Reward (Champions, Loyal)
- Re-engage (At Risk)
- Let go (Lost)

This task demonstrates key skills in:

- Cleaning transaction-level data
- Customer-level behavioral analysis
- Creating data-driven marketing segments

---


