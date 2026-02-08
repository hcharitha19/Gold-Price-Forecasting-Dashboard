# 📂 Dataset Information

This folder contains all datasets used in the **Gold Price Forecasting & Analysis Dashboard**.

---

## 📄 Files Description

### 1️⃣ gold_price_forecasting_dataset.csv
- Primary dataset used for analysis
- Contains historical gold price data
- Includes:
  - Date
  - Open Price
  - High Price
  - Low Price
  - Close Price
  - Volume
  - RSI
  - Volatility metrics

---

### 2️⃣ Fact_Gold_Prices.csv
- Fact table used in Power BI data model
- Granular daily gold price data
- Connected to Dim_Date using Date key

---

### 3️⃣ Dim_Date.csv
- Date dimension table
- Contains:
  - Date
  - Year
  - Month
  - Month Name
  - Quarter

---

### 4️⃣ Dim_Metrics.csv
- Metric selection table for dynamic KPIs
- Used to switch between:
  - Close Price
  - High Price
  - Low Price
  - Open Price

---

## 💱 Units & Notes
- All prices are in **Indian Rupees (₹ INR)**
- RSI values range from **0 to 100**
- Data frequency: **Daily**

---

## 📅 Data Freshness
- Dashboard last updated date is dynamically calculated using the **maximum date** from `Dim_Date`

---

## 🔗 Usage
These datasets are directly connected to the Power BI report (`.pbix`) and should not be modified unless data refresh is required.
These datasets are directly connected to the Power BI report (`.pbix`) and should not be modified unless data refresh is required.

## Learning Reference:
Codebasics (data analytics Bootcamp) 
👉https://codebasics.io/
