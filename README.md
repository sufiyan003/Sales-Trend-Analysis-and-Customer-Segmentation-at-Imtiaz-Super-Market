<div align="center">

<img src="https://img.shields.io/badge/-%F0%9F%9B%92%20IMTIAZ%20SUPER%20MARKET-F7941D?style=for-the-badge&labelColor=0D1117&color=F7941D" alt="Imtiaz"/>

# Sales Trend Analysis & Customer Segmentation
### at Imtiaz Super Market, Karachi

*A Complete End-to-End Data Warehousing & Mining Project*

<br/>

![Python](https://img.shields.io/badge/Python-3.13-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Snowflake](https://img.shields.io/badge/Snowflake-AWS_Enterprise-29B5E8?style=for-the-badge&logo=snowflake&logoColor=white)
![PowerBI](https://img.shields.io/badge/Power_BI-Interactive_Dashboard-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

<br/>

![Pandas](https://img.shields.io/badge/Pandas-ETL_Pipeline-150458?style=flat-square&logo=pandas&logoColor=white)
![Scikit](https://img.shields.io/badge/Scikit--learn-Data_Mining-F7931E?style=flat-square&logo=scikit-learn&logoColor=white)
![Mlxtend](https://img.shields.io/badge/Mlxtend-Apriori-FF6B6B?style=flat-square)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4C72B0?style=flat-square)

<br/>

> **"Transforming 17,513 retail transactions into actionable business intelligence"**
> 
> *Python • Snowflake • Power BI • scikit-learn • Apriori*

</div>

---

## 📋 Table of Contents

- [Project Overview](#-project-overview)
- [Key Results](#-key-results)
- [Architecture](#-architecture)
- [Power BI Dashboard](#-power-bi-dashboard)
- [Data Warehouse — Star Schema](#-data-warehouse--star-schema)
- [ETL Pipeline](#-etl-pipeline)
- [Data Mining Techniques](#-data-mining-techniques)
- [Key Business Insights](#-key-business-insights)
- [Repository Structure](#-repository-structure)
- [Tech Stack](#-tech-stack)
- [Getting Started](#-getting-started)
- [Author](#-author)

---

## 🏢 Project Overview

**Imtiaz Super Market** — founded in **1955** — is one of Pakistan's most trusted retail chains operating **6 branches across Karachi**. Despite generating thousands of daily transactions, the organization lacked structured analytical capability.

This project delivers a **production-grade data pipeline** that transforms raw retail data into strategic business intelligence — from ETL and cloud data warehousing to advanced machine learning and interactive dashboards.

### 🎯 Business Challenges Solved

| Challenge | Solution |
|-----------|----------|
| No visibility into customer value | K-Means Clustering + Random Forest Classification |
| Unknown product co-purchase patterns | Apriori Association Rule Mining |
| No sales forecasting capability | Linear Regression — 6-month forecast |
| Raw data scattered with no warehouse | Snowflake Star Schema Data Warehouse |
| No executive-level reporting | 3-Page Power BI Dashboard |

---

## ⚡ Key Results

<div align="center">

| 📊 Metric | 💡 Value |
|-----------|---------|
| 💰 Total Sales | **PKR 19.04 Million** |
| 📦 Total Transactions | **17,513 rows** |
| 👥 Unique Customers | **500** |
| 🏪 Karachi Branches | **6** |
| 🗂️ Product Categories | **12** |
| 🎯 ML Classification Accuracy | **94% (Random Forest)** |
| 🔗 Association Rules Discovered | **123 rules** |
| 📈 Sep 2026 Sales Forecast | **PKR 1,336,329/month** |
| ⭐ Top Rule Lift Score | **1.21 (Grocery + Bakery)** |
| 🤝 Loyalty Members | **65% of customers** |

</div>

---

## 🏗️ Architecture

```
╔══════════════════════════════════════════════════════════════╗
║          IMTIAZ SUPER MARKET — DATA PIPELINE                 ║
╠══════════════════════════════════════════════════════════════╣
║                                                              ║
║   🌐 Imtiaz Website (shop.imtiaz.com.pk)                    ║
║              ↓  Product catalog verification                 ║
║   🐍 Python — Synthetic Dataset Generation                   ║
║      Real categories | PKR prices | Karachi areas            ║
║              ↓  17,513 rows | 27 columns                     ║
║   🔄 Python + Pandas — ETL Pipeline                          ║
║      Extract → Transform → Load                              ║
║              ↓  5 Star Schema tables                         ║
║   ❄️  Snowflake Cloud Data Warehouse (AWS)                   ║
║      IMTIAZ_DW.RETAIL — Star Schema                          ║
║              ↓  Python scikit-learn + mlxtend                ║
║   🧠 Data Mining — 4 Techniques                              ║
║      Classification | Clustering | Rules | Regression        ║
║              ↓  Import Mode                                  ║
║   📊 Power BI — 3-Page Interactive Dashboard                 ║
║      Sales | Customers | Mining Results                      ║
╚══════════════════════════════════════════════════════════════╝
```

---

## 📊 Power BI Dashboard

> **Tool:** Power BI Desktop | **Connection:** Snowflake Import Mode
> **Theme:** Dark (#0D1117) | **Brand Colors:** Orange #F7941D + Blue #003087

### 🔷 Page 1 — Sales Overview

![Sales Overview Dashboard](https://raw.githubusercontent.com/sufiyan003/Sales-Trend-Analysis-and-Customer-Segmentation-at-Imtiaz-Super-Market/refs/heads/main/dashboard/Page%201.jpg)

**Visuals included:**
- 📦 KPI Cards — Total Sales (PKR 19.04M) | Profit (PKR 3.13M) | Orders (3,861) | Customers (500)
- 📈 Monthly Sales Trend — 2025 vs 2026 line chart
- 📊 Sales by Category — Grocery leads at PKR 3.0M
- 🍩 Payment Method Distribution — Cash 32.79% | JazzCash 17.24%
- 🏆 Top 5 Products by Sales

---

### 🔷 Page 2 — Customer Segments

![Customer Segments Dashboard](https://raw.githubusercontent.com/sufiyan003/Sales-Trend-Analysis-and-Customer-Segmentation-at-Imtiaz-Super-Market/refs/heads/main/dashboard/Page%202.jpg)

**Visuals included:**
- 🍩 Customer Segment Distribution — Mid Value 55.4%
- 📊 Sales by Customer Segment — Mid Value PKR 9.8M
- 📍 Customers by Karachi Area — North Nazimabad top (49)
- 💎 Loyalty Member Distribution — 65% members

---

### 🔷 Page 3 — Mining Results

![Mining Results Dashboard](https://raw.githubusercontent.com/sufiyan003/Sales-Trend-Analysis-and-Customer-Segmentation-at-Imtiaz-Super-Market/refs/heads/main/dashboard/Page%203.jpg)

**Visuals included:**
- 📊 Top Categories by Orders — Grocery 1,895
- 📈 Monthly Profit Trend
- 🍩 Delivery Type — In-Store 59.28% | Home Delivery 40.72%
- 💰 Profit by Category — Grocery PKR 0.49M

---

## 🗄️ Data Warehouse — Star Schema

```
                         ┌──────────────────┐
                         │    DimTime       │
                         │   470 rows       │
                         │  date_key (PK)   │
                         │  month | year    │
                         │  quarter|season  │
                         └────────┬─────────┘
                                  │ date_key
                                  │
┌─────────────────┐    ┌──────────┴──────────┐    ┌─────────────────┐
│  DimCustomer    │    │      FactSales       │    │   DimProduct    │
│   500 rows      │    │    17,513 rows  ⭐   │    │   112 rows      │
│ customer_key PK │────│  customer_key (FK)  │────│ product_key PK  │
│ name | gender   │    │  product_key  (FK)  │    │ product_name    │
│ area | segment  │    │  store_key    (FK)  │    │ category        │
│ loyalty_member  │    │  date_key     (FK)  │    └─────────────────┘
└─────────────────┘    │  sales_pkr          │
                       │  profit_pkr         │
                       │  quantity           │    ┌─────────────────┐
                       │  payment_method     │    │   DimStore      │
                       │  delivery_type      │────│   6 rows        │
                       └─────────────────────┘    │ store_key PK    │
                                                  │ store_name      │
                                                  │ store_city      │
                                                  └─────────────────┘
```

### ❄️ Snowflake Configuration

```sql
Database  : IMTIAZ_DW
Schema    : RETAIL
Warehouse : IMTIAZ_WH  (X-Small | Auto-suspend: 60s)
Cloud     : AWS Enterprise Edition
Account   : UYZXLTU-JRB82315
```

### 📋 Table Summary

| Table | Type | Rows | Primary Key |
|-------|------|------|-------------|
| `FACTSALES` | ⭐ Fact | 17,513 | order_id |
| `DIMCUSTOMER` | Dimension | 500 | customer_key |
| `DIMPRODUCT` | Dimension | 112 | product_key |
| `DIMSTORE` | Dimension | 6 | store_key |
| `DIMTIME` | Dimension | 470 | date_key |

---

## 🔄 ETL Pipeline

### Step 1 — Extract

```python
import pandas as pd

df = pd.read_csv("Imtiaz_Supermarket_Dataset_2025_2026.csv")

print(f"Rows    : {df.shape[0]:,}")   # 17,513
print(f"Columns : {df.shape[1]}")     # 27
print(f"Range   : {df['order_date'].min()} → {df['order_date'].max()}")
# Range: 2025-01-01 → 2026-04-15
```

### Step 2 — Transform

```python
# ✅ Fix data types
df['order_date'] = pd.to_datetime(df['order_date'])

# ✅ Data quality check
print(f"Missing values : {df.isnull().sum().sum()}")   # 0
print(f"Duplicates     : {df.duplicated().sum()}")     # 0

# ✅ Add Season column (Pakistan context)
def get_season(month):
    if month in [12, 1, 2]:  return 'Winter'
    elif month in [3, 4, 5]: return 'Spring/Ramazan'
    elif month in [6, 7, 8]: return 'Summer'
    else:                     return 'Autumn'

# ✅ Customer Segmentation
# High Value  : Total spend ≥ PKR 50,000  → 129 customers
# Mid Value   : PKR 20,000 – 49,999       → 277 customers
# Low Value   : Below PKR 20,000          → 94 customers
```

### Step 3 — Load to Snowflake

```python
import snowflake.connector
from snowflake.connector.pandas_tools import write_pandas

conn = snowflake.connector.connect(
    user='SUFIYAN003', account='UYZXLTU-JRB82315',
    warehouse='IMTIAZ_WH', database='IMTIAZ_DW', schema='RETAIL'
)

# Load all 5 Star Schema tables
write_pandas(conn, dim_customer, 'DIMCUSTOMER')  # ✅ 500 rows
write_pandas(conn, dim_product,  'DIMPRODUCT')   # ✅ 112 rows
write_pandas(conn, dim_store,    'DIMSTORE')     # ✅ 6 rows
write_pandas(conn, dim_time,     'DIMTIME')      # ✅ 470 rows
write_pandas(conn, fact_sales,   'FACTSALES')    # ✅ 17,513 rows
```

---

## 🧠 Data Mining Techniques

### 1. 🎯 Classification — Random Forest

> **Goal:** Predict customer value segment (High / Mid / Low Value)

```
Algorithm    : Random Forest Classifier
n_estimators : 100 trees
Train / Test : 400 (80%) / 100 (20%) — stratified split
Accuracy     : 94%
Top Feature  : total_items (importance score: 0.41)
```

**📊 Confusion Matrix**

![Confusion Matrix](https://raw.githubusercontent.com/sufiyan003/Sales-Trend-Analysis-and-Customer-Segmentation-at-Imtiaz-Super-Market/refs/heads/main/outputs/classification_confusion_matrix.png)

**📊 Feature Importance**

![Feature Importance](https://raw.githubusercontent.com/sufiyan003/Sales-Trend-Analysis-and-Customer-Segmentation-at-Imtiaz-Super-Market/refs/heads/main/outputs/feature_importance.png)

**Classification Report:**

| Segment | Precision | Recall | F1-Score | Support |
|---------|-----------|--------|----------|---------|
| High Value | 1.00 | 1.00 | 1.00 | 26 |
| Mid Value | 0.93 | 0.96 | 0.95 | 55 |
| Low Value | 0.88 | 0.79 | 0.83 | 19 |
| **Accuracy** | | | **0.94** | **100** |

> **Note:** Initial model showed 100% accuracy due to feature leakage (total_spend directly defined segments). After removing correlated features, model achieved realistic **94% accuracy** — demonstrating proper ML practices.

---

### 2. 🔵 Clustering — K-Means

> **Goal:** Discover natural customer groups based on shopping behavior — unsupervised

```
Algorithm        : K-Means Clustering
Optimal k        : 3 (Elbow Method)
Silhouette Score : 0.2933
Preprocessing    : StandardScaler
Features         : total_spend | total_orders | avg_order_val
                   total_items | avg_discount
```

**📊 Elbow Method — Optimal k Selection**

![Elbow Method](https://raw.githubusercontent.com/sufiyan003/Sales-Trend-Analysis-and-Customer-Segmentation-at-Imtiaz-Super-Market/refs/heads/main/outputs/elbow_method.png)

**📊 K-Means Customer Clusters**

![K-Means Clusters](https://raw.githubusercontent.com/sufiyan003/Sales-Trend-Analysis-and-Customer-Segmentation-at-Imtiaz-Super-Market/refs/heads/main/outputs/kmeans_clusters.png)

**📊 Cluster Distribution**

![Cluster Distribution](https://raw.githubusercontent.com/sufiyan003/Sales-Trend-Analysis-and-Customer-Segmentation-at-Imtiaz-Super-Market/refs/heads/main/outputs/cluster_distribution.png)

**Cluster Results:**

| Cluster | Customers | Avg Spend | Avg Orders | Avg Items |
|---------|-----------|-----------|------------|-----------|
| 🟢 High Spenders | 231 | PKR 53,263 | 10.27 | 120.43 |
| 🔴 Low Spenders | 155 | PKR 21,963 | 5.82 | 59.48 |
| 🔵 Mid Spenders | 114 | PKR 29,248 | 5.15 | 57.83 |

---

### 3. 🛒 Association Rules — Apriori

> **Goal:** Market Basket Analysis — discover co-purchased product categories

```
Algorithm         : Apriori
Min Support       : 0.05  (5% of 3,861 orders)
Min Confidence    : 0.30
Min Lift          : 1.0
Frequent Itemsets : 102
Rules Generated   : 123
```

**📊 Top 10 Association Rules by Lift**

![Association Rules](https://raw.githubusercontent.com/sufiyan003/Sales-Trend-Analysis-and-Customer-Segmentation-at-Imtiaz-Super-Market/refs/heads/main/outputs/association_rules.png)

**📊 Support vs Confidence — Scatter Plot**

![Association Scatter](https://raw.githubusercontent.com/sufiyan003/Sales-Trend-Analysis-and-Customer-Segmentation-at-Imtiaz-Super-Market/refs/heads/main/outputs/association_scatter.png)

**Top Rules:**

| Antecedent | Consequent | Support | Confidence | Lift |
|------------|------------|---------|------------|------|
| Grocery + Bakery | Clothing & Fabric | 0.058 | 0.33 | **1.21** |
| Clothing + Grocery | Bakery | 0.058 | 0.40 | 1.19 |
| Fruits & Veg + Grocery | Meat & Seafood | 0.066 | 0.33 | 1.17 |
| Personal Care + Grocery | Bakery | 0.057 | 0.39 | 1.17 |

> 🛒 **Grocery** appears in **49% of all orders** — primary store traffic driver

---

### 4. 📈 Regression — Sales Forecasting

> **Goal:** Predict future monthly sales using historical trend data

```
Algorithm     : Linear Regression (y = mx + c)
Training Data : Jan 2025 – Mar 2026  (15 months)
Forecast      : Apr 2026 – Sep 2026  (6 months)
Note          : April 2026 removed from training — incomplete month
```

**📊 Monthly Sales Trend & Forecast**

![Sales Forecast](https://raw.githubusercontent.com/sufiyan003/Sales-Trend-Analysis-and-Customer-Segmentation-at-Imtiaz-Super-Market/refs/heads/main/outputs/sales_forecast.png)

**6-Month Sales Forecast:**

| Month | Projected Sales |
|-------|----------------|
| April 2026 | PKR 1,300,957 |
| May 2026 | PKR 1,308,031 |
| June 2026 | PKR 1,315,106 |
| July 2026 | PKR 1,322,180 |
| August 2026 | PKR 1,329,254 |
| **September 2026** | **PKR 1,336,329** |

> 📈 **Steady upward trend** — consistent month-over-month growth projected

---

### 5. 🌡️ Correlation Heatmap

> **Goal:** Identify relationships between numerical features

**📊 Correlation Heatmap**

![Correlation Heatmap](https://raw.githubusercontent.com/sufiyan003/Sales-Trend-Analysis-and-Customer-Segmentation-at-Imtiaz-Super-Market/refs/heads/main/outputs/correlation_heatmap.png)

**Key Correlations:**

| Feature Pair | Correlation | Interpretation |
|--------------|-------------|----------------|
| sales_pkr ↔ profit_pkr | **0.93** | 🟢 Strong — sales directly drives profit |
| unit_price_pkr ↔ sales_pkr | **0.84** | 🟢 Strong — premium products = higher revenue |
| discount_pct ↔ discount_amount | **0.56** | 🟡 Moderate — expected relationship |
| quantity ↔ sales_pkr | **0.38** | 🟡 Moderate — volume contributes to sales |

---

## 💡 Key Business Insights

| # | 🔍 Insight | 📊 Data Point | 💼 Business Action |
|---|-----------|--------------|-------------------|
| 1 | 🛒 Grocery dominates | PKR 3.0M sales, 1,895 orders | Maintain stock, premium placement |
| 2 | 👥 Mid Value customers key | 55.4% base, PKR 9.8M revenue | Loyalty rewards to upgrade to High |
| 3 | 💳 Digital payments rising | JazzCash+EasyPaisa+Card = 50%+ | Expand mobile payment infrastructure |
| 4 | ⭐ Loyalty program effective | 65% members | Personalized offers for members |
| 5 | 🔗 Grocery+Bakery combo | Lift score 1.21 | Co-locate sections in store |
| 6 | 📍 North Nazimabad leads | 49 customers (top branch) | Increase investment in this branch |
| 7 | 📈 Growth trajectory | PKR 1.34M forecast Sep 2026 | Plan inventory for growth |
| 8 | 🚚 Home delivery significant | 40.72% of orders | Improve delivery infrastructure |

---

## 📁 Repository Structure

```
📦 Sales-Trend-Analysis-and-Customer-Segmentation-at-Imtiaz-Super-Market
│
├── 📂 data/
│   ├── 📄 Imtiaz_Supermarket_Dataset_2025_2026.csv  ← Raw dataset (17,513 rows)
│   ├── 📄 dim_customer.csv                           ← DimCustomer (500 rows)
│   ├── 📄 dim_product.csv                            ← DimProduct (112 rows)
│   ├── 📄 dim_store.csv                              ← DimStore (6 rows)
│   ├── 📄 dim_time.csv                               ← DimTime (470 rows)
│   └── 📄 fact_sales.csv                             ← FactSales (17,513 rows)
│
├── 📂 etl/
│   └── 📓 etl.ipynb                                  ← Complete ETL pipeline
│
├── 📂 mining/
│   └── 📓 mining.ipynb                               ← All 4 mining techniques
│
├── 📂 outputs/
│   ├── 🖼️ classification_confusion_matrix.png        ← Random Forest results
│   ├── 🖼️ feature_importance.png                     ← Feature importance chart
│   ├── 🖼️ elbow_method.png                           ← K selection chart
│   ├── 🖼️ kmeans_clusters.png                        ← Cluster scatter plot
│   ├── 🖼️ cluster_distribution.png                   ← Cluster bar chart
│   ├── 🖼️ association_rules.png                      ← Top rules bar chart
│   ├── 🖼️ association_scatter.png                    ← Support vs Confidence
│   ├── 🖼️ sales_forecast.png                         ← Regression forecast
│   ├── 🖼️ correlation_heatmap.png                    ← Feature correlations
│   ├── 🖼️ dashboard_page1_sales_overview.png         ← Power BI Page 1
│   ├── 🖼️ dashboard_page2_customer_segments.png      ← Power BI Page 2
│   └── 🖼️ dashboard_page3_mining_results.png         ← Power BI Page 3
│
└── 📄 README.md
```

---

## 🛠️ Tech Stack

| Layer | Technology | Version | Purpose |
|-------|-----------|---------|---------|
| 🐍 Language | Python | 3.13 | Core development |
| 📊 Data Processing | Pandas | Latest | ETL & transformation |
| 🔢 Numerics | NumPy | Latest | Array operations |
| 🤖 ML — Classification | Scikit-learn | Latest | Random Forest |
| 🔵 ML — Clustering | Scikit-learn | Latest | K-Means |
| 📈 ML — Regression | Scikit-learn | Latest | Linear Regression |
| 🛒 Association Rules | Mlxtend | Latest | Apriori algorithm |
| 📉 Visualization | Matplotlib | Latest | Charts & plots |
| 🌡️ Heatmap | Seaborn | Latest | Correlation heatmap |
| ❄️ Data Warehouse | Snowflake | Enterprise | Cloud DW (AWS) |
| 🔌 DB Connector | Snowflake Connector | Latest | Python → Snowflake |
| 📊 Dashboard | Power BI Desktop | Latest | Interactive dashboard |
| 💡 DAX | Power BI DAX | - | Custom measures |
| 💻 IDE | Jupyter Notebook | Latest | Development |
| 🗄️ Schema Design | dbdiagram.io | - | ER Diagram |

---

## 🚀 Getting Started

### Prerequisites

```bash
pip install pandas numpy scikit-learn mlxtend matplotlib seaborn snowflake-connector-python jupyter
```

### Step 1 — Run ETL Pipeline

```bash
cd etl
jupyter notebook etl.ipynb
# Run all cells sequentially
# Output: 5 CSV files saved in data/ folder
```

### Step 2 — Setup Snowflake

```sql
-- Run in Snowflake Worksheet
CREATE WAREHOUSE IMTIAZ_WH WAREHOUSE_SIZE='X-SMALL' AUTO_SUSPEND=60 AUTO_RESUME=TRUE;
CREATE DATABASE IMTIAZ_DW;
CREATE SCHEMA IMTIAZ_DW.RETAIL;

-- Create all 5 tables (DDL in etl.ipynb)
-- Load data using Python connector (Cell 24-31 in etl.ipynb)
```

### Step 3 — Run Data Mining

```bash
cd mining
jupyter notebook mining.ipynb
# Run all cells sequentially
# Output: 9 charts saved in outputs/ folder
```

### Step 4 — Power BI Dashboard

```
1. Open Power BI Desktop
2. Home → Get Data → Snowflake
3. Server: UYZXLTU-JRB82315.snowflakecomputing.com
4. Select: Import Mode
5. Load: DIMCUSTOMER, DIMPRODUCT, DIMSTORE, DIMTIME, FACTSALES
6. Model View: Set 4 relationships (Many-to-One)
7. Create _Measures table with DAX measures
8. Build 3-page dashboard
```

---

## 📊 Dataset Details

| Attribute | Value |
|-----------|-------|
| Total Records | 17,513 rows |
| Unique Customers | 500 |
| Unique Orders | 3,861 |
| Date Range | January 2025 – April 2026 |
| Product Categories | 12 |
| Store Branches | 6 (Karachi) |
| Columns | 27 |
| Currency | Pakistani Rupees (PKR) |
| Generation Method | Synthetic — based on actual Imtiaz catalog |
| Source Reference | [shop.imtiaz.com.pk](https://shop.imtiaz.com.pk) |

**12 Product Categories:**
`Grocery` `Fruits & Vegetables` `Bakery` `Meat & Seafood` `Dairy` `Pharmacy & Health` `Electronics` `Household` `Personal Care` `Clothing & Fabric` `Stationery` `Toys & Sports`

**6 Karachi Branches:**
`Bahadurabad` `Nazimabad` `DHA` `Clifton` `Gulshan-e-Iqbal` `Sharafabad`

---

## 📚 References

```
Agrawal, R., & Srikant, R. (1994). Fast algorithms for mining association rules.
  Proceedings of the 20th VLDB Conference, 487-499.

Breiman, L. (2001). Random forests.
  Machine Learning, 45(1), 5-32. https://doi.org/10.1023/A:1010933404324

Han, J., Kamber, M., & Pei, J. (2011). Data mining: Concepts and techniques (3rd ed.).
  Morgan Kaufmann.

Kimball, R., & Ross, M. (2013). The data warehouse toolkit (3rd ed.).
  Wiley.

Imtiaz Super Market. (2026). Online shopping. https://shop.imtiaz.com.pk/

Pedregosa, F., et al. (2011). Scikit-learn: Machine learning in Python.
  Journal of Machine Learning Research, 12, 2825-2830.

Raschka, S. (2018). MLxtend. Journal of Open Source Software, 3(24), 638.

Snowflake Inc. (2026). Snowflake documentation. https://docs.snowflake.com/

Microsoft. (2026). Power BI documentation. https://docs.microsoft.com/power-bi/
```

---

## 👤 Author

<div align="center">

### Muhammad Sufiyan Siddiqui

*BS Computer Science — University of Karachi (UBIT)*
*Data Analyst | Data Engineer | Python Developer*

<br/>

[![GitHub](https://img.shields.io/badge/GitHub-sufiyan003-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/sufiyan003)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Muhammad_Sufiyan-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/muhammad-sufiyan-2a741b311)

<br/>

*BSCS-636 — Data Warehousing & Data Mining*
*Instructor: Dr. Taha Sabir | University of Karachi (UBIT) | May 2026*

<br/>

---

*⭐ If you found this project helpful, please give it a star!*

</div>
