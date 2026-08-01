# 🚀 Day 3: Advanced NumPy Operations with Business Examples

Welcome to **Day 3**! Today focuses on applying NumPy to real-world business scenarios, data analysis, sales metrics, linear algebra concepts, and visualization.

---

## 📌 Table of Contents

1. [Total Sales per Year](#1-total-sales-per-year)
2. [Min, Max, and Average Sales](#2-min-max-avg-sales)
3. [Cumulative Sales & Matplotlib Graphs](#3-cumulative-sales--matplotlib-graphs)
4. [Vector Addition and Multiplication](#4-vector-addition-and-multiplication)
5. [Vectorized String Operations (Upper Case)](#5-vectorized-upper)
6. [Monthly Average Analysis](#6-monthly-average-analysis)

---

## 1. Total Sales per Year
Calculating aggregated annual sales data across different regions/products using `np.sum()` along specific axes.

---

## 2. Min, Max, Avg Sales
Extracting business performance metrics:
* `np.min()` – Identifying lowest sales periods.
* `np.max()` – Finding peak revenue.
* `np.mean()` – Computing overall average sales performance.

---

## 3. Cumulative Sales and Matplotlib Graphs
* **Cumulative Sum (`np.cumsum()`):** Tracking running totals of sales over time.
* **Data Visualization:** Plotting sales trends and growth curves using Matplotlib (`plt.plot()`).

---

## 4. Vector Addition and Multiplication
Performing fast element-wise math operations and linear algebra concepts for financial computations (e.g., applying tax rates, price × quantity vectors).

---

## 5. Vectorized Upper
Applying vectorized string manipulation functions (e.g., `np.char.upper()`) on array data for clean text formatting without loops.

---

## 6. Monthly Average
Analyzing seasonal trends by aggregating multi-month data and calculating monthly averages using column/row-wise array operations (`axis=0` / `axis=1`).

---

## 🛠️ Requirements & Setup

Make sure you have NumPy and Matplotlib installed:

```bash
pip install numpy matplotlib