# 🔍 Customer Segmentation & Seasonal Demand Forecasting

**Real-World Business Analytics Project | VP Fire and Security System Pvt. Ltd.**
<img width="814" alt="image" src="https://github.com/user-attachments/assets/ba3821d0-d8a5-49b1-bea5-6ce0e3402653" />


## 📌 Overview

This project was conducted as part of a collaborative initiative with **VP Fire and Security System Pvt. Ltd.**, focusing on deriving actionable business insights from real-world customer and sales data. The project addressed the following three business challenges:

---

## 🧩 Business Problem Statements

1. **Forecasting Seasonal Demand**
   The company faced difficulties forecasting demand spikes—especially during festive seasons like November—leading to inventory shortages and understaffing, which in turn caused missed sales opportunities.

2. **Customer Base Understanding**
   VP Fire lacked a data-driven understanding of its customer base, resulting in inefficient marketing strategies and limited personalized engagement across segments.

3. **Market Visibility**
   As a relatively new player in the market, the company struggled with visibility and brand recognition in lucrative sectors such as hotels and hospitals, limiting growth.

---

## 🎯 Project Objectives

* Build a **segmentation strategy** based on customer purchasing behavior to enhance retention and engagement.
* Develop **time series models** to forecast seasonal demand fluctuations.
* Generate **strategic recommendations** using insights derived from data, aligned with business needs.

---

## 🔍 Key Analytics Modules

### 1. Customer Segmentation

* **Techniques Used**:

  * RFM (Recency, Frequency, Monetary) Scoring
  * K-Means Clustering
* **Insights & Output**:

  * Identified VIP, Loyal, and At-Risk customer segments
  * Suggested relationship-based retention strategies, win-back campaigns, and CRM enhancement

### 2. Seasonal Demand Forecasting

* **Techniques Used**:

  * Time Series Decomposition
  * ADF Test for stationarity
  * SARIMA Modeling
* **Best Model**: SARIMA(1,1,2)(1,0,1)\[7]
* **Performance Metrics**:

  * **AIC**: 520.94
  * **MAE**: 113,641.08
  * **WAPE**: 101.82%
* **Application**: Forecasted weekly demand to guide inventory stocking and manpower allocation

---

## 📈 Estimated Business Impact

* Potential **20% increase in customer retention and reactivation** through tailored engagement strategies
* Minimized **stock-outs and service delays** during high-demand periods
* Improved **market reach** through product-specific and cross-promotional campaign strategies

---

## 🧰 Tools & Technologies

* **Languages**: Python, SQL
* **Libraries**: Pandas, NumPy, Scikit-learn, Statsmodels, Matplotlib, Seaborn
* **Platform**: Jupyter Notebook
* **Techniques**: Clustering, RFM Analysis, Time Series Forecasting (SARIMA)

---

## 📌 Disclaimer

> ⚠️ This was an academic-industry collaborative project using real but anonymized business data.
> The insights were generated in an exploratory capacity and not deployed to live production systems.
