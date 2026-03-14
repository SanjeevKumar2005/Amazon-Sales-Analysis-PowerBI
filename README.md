# 🛍️ Amazon Products Sales Analysis - Power BI Dashboard


## 📋 Project Overview
An interactive Power BI dashboard providing comprehensive sales analysis for Amazon products across multiple categories. This project transforms raw sales data into actionable insights through dynamic visualizations and KPIs.

---

## 🎯 Key Performance Indicators

| Metric | Value |
|--------|-------|
| **YTD Sales** | $2.18M |
| **QTD Sales** | $811.09K |
| **YTD Products Sold** | 27.75K |
| **YTD Reviews** | 19.42M |

---

## 📊 Product Category Analysis

### Sales Distribution by Category

| Category | YTD Sales | QTD Sales | % of Total |
|----------|-----------|-----------|------------|
| **👟 Men Shoes** | **$940,266** | **$325,090** | **43.18%** |
| 📷 Camera | $492,521 | $188,381 | 22.62% |
| 👔 Men Clothes | $357,644 | $136,700 | 16.42% |
| 🚗 Car Accessories | $237,290 | $91,359 | 10.90% |
| 🧸 Toys | $110,839 | $38,382 | 5.09% |
| 📱 Mobile & Accessories | $39,178 | $39,178 | 1.80% |
| | | | |
| **TOTAL** | **$2,177,738** | **$811,090** | **100%** |

### Key Category Insights
- **Men Shoes** dominates with nearly half (43.18%) of total YTD sales
- **Camera** and **Men Clothes** together contribute 39% of sales
- **Mobile & Accessories** has the lowest share at 1.80%

---

## 🏆 Top Performers

### Top 5 Products by YTD Sales

| Rank | Product | Sales ($K) | Category |
|:----:|---------|:----------:|----------|
| **#1** | Nikon Wide Angle Lens | **$34K** | 📷 Camera |
| **#2** | Atomos Ninja Monitor | **$28K** | 📷 Camera |
| **#3** | Solid Gear Boots | **$27K** | 👟 Men Shoes |
| **#4** | Canal Toys Set | **$22K** | 🧸 Toys |
| **#5** | Vince Camuto Loafers | **$19K** | 👟 Men Shoes |

### Top 5 Products by Customer Reviews

| Rank | Product | Reviews | Category |
|:----:|---------|:-------:|----------|
| **#1** | SanDisk 1TB SSD | **0.40M** | 📷 Camera |
| **#2** | SanDisk 128GB Card | **0.34M** | 📷 Camera |
| **#3** | SanDisk 4TB External | **0.23M** | 📷 Camera |
| **#4** | JTech Screen Protector | **0.16M** | 📱 Mobile |
| **#5** | WOLVERINE Boots | **0.14M** | 👟 Men Shoes |

### Top Performers Insights
- **Nikon** and **SanDisk** are the dominant brands
- Camera category leads in both sales and reviews
- Men Shoes shows strong sales performance
- Storage products generate maximum customer engagement

---

## 📅 Time-Based Analysis

### Monthly Sales Trend

| Month | Sales | Trend |
|-------|-------|-------|
| January | $0.3M | 📉 |
| February | $0.2M | 📉 |
| March | $0.5M | 📈 |
| April | $0.5M | ➡️ |
| May | $0.6M | 📈 |
| June | $0.6M | ➡️ |
| July | $0.5M | 📉 |
| August | $0.5M | ➡️ |
| September | $1.2M | 📈 |
| October | $0.8M | 📉 |
| November | $1.2M | 📈 |
| December | $1.3M | 📈 |

### Monthly Sales Insights
- **Highest Sales**: December ($1.3M)
- **Lowest Sales**: February ($0.2M)
- **Peak Season**: Q4 (Sep-Dec) shows significant spike
- **Growth Trend**: 333% increase from Feb to Dec

### Weekly Sales Pattern
- Week-over-week analysis shows consistent sales
- Average weekly sales: $0.1M - $0.3M
- Highest weekly sales: Week 100 at $0.65M
- Seasonal peaks during holiday weeks

---

## 📁 Dataset Description

### Data Sources

The project uses multiple CSV files containing Amazon product sales data:

#### Main Dataset: `Amazon_Sales_Data.csv`
Contains 27 records of Men Shoes products with the following fields:
- **Product Category**: Product classification
- **Product Description**: Detailed product name and features
- **Price**: Product price in USD ($28 - $275)
- **Number of Reviews**: Customer review count
- **Shipment**: Shipping destination
- **Order Date**: Purchase date (Feb - Nov 2022)

#### Summary Files:

| File Name | Description | Key Fields |
|-----------|-------------|------------|
| `Category_Summary.csv` | Sales by product category | Category, YTD_Sales, QTD_Sales, Percentage |
| `Top_Products.csv` | Top performing products | Product_Name, Sales_Amount, Category, Type |
| `Monthly_Sales.csv` | Month-wise sales trend | Month_Name, Month_Number, Sales_Amount |
| `Weekly_Sales.csv` | Week-wise sales breakdown | Week_Number, Sales_Amount |

### Data Dictionary

| Field Name | Description | Data Type | Example |
|------------|-------------|-----------|---------|
| Product Category | Main product classification | Text | "Men Shoes" |
| Product Description | Full product name with details | Text | "KEEN Men's Hiking Shoes" |
| Price | Product price in USD | Currency | 141.00 |
| Number of Reviews | Total customer reviews | Integer | 1 |
| Shipment | Shipping destination | Text | "Ships to Bangladesh" |
| Order Date | Date of purchase | Date | "03-02-2022" |
| YTD_Sales | Year-to-date sales amount | Currency | 940266 |
| QTD_Sales | Quarter-to-date sales amount | Currency | 325090 |
| Percentage | Category sales percentage | Percentage | 43.18% |

### Data Summary

| Metric | Value |
|--------|-------|
| Total Records (Main Table) | 27 products |
| Date Range | Feb 2022 - Nov 2022 |
| Price Range | $28 - $275 |
| Total Categories | 6 categories |
| Total YTD Sales | $2.18 Million |
| Total Products Sold | 27.75K units |
| Total Reviews | 19.42 Million |


## 📅 Monthly & Weekly Sales Analysis

### 📊 Monthly Sales Overview

| Month | Sales (USD) | Performance |
|-------|:-----------:|:-----------:|
| January | $300,000 | 🟡 Moderate |
| February | $200,000 | 🔴 Low |
| March | $500,000 | 🟢 Good |
| April | $500,000 | 🟢 Good |
| May | $600,000 | 🟢 Good |
| June | $600,000 | 🟢 Good |
| July | $500,000 | 🟢 Good |
| August | $500,000 | 🟢 Good |
| September | $1,200,000 | 🔥 Peak |
| October | $800,000 | 🟡 Moderate |
| November | $1,200,000 | 🔥 Peak |
| December | $1,300,000 | 🔥 Peak |

**Key Monthly Insights:**
- 🔥 **Peak Month**: December ($1.3M) - Holiday season
- 📉 **Lowest Month**: February ($0.2M) - Post-holiday dip
- 📈 **Best Quarter**: Q4 (Oct-Dec) with $3.3M total

---

### 📊 Weekly Sales Highlights

| Top Weeks | Sales | Month |
|:---------:|:-----:|:-----:|
| Week 100 | $650,000 | December |
| Week 99 | $640,000 | December |
| Week 98 | $630,000 | December |
| Week 97 | $620,000 | November |
| Week 96 | $610,000 | November |
| Week 95 | $600,000 | November |

**Key Weekly Insights:**
- 🏆 **Highest Week**: Week 100 ($650K)
- 📈 **Growth**: 3,150% increase from Week 1 to Week 100
- 🎯 **Peak Season**: Weeks 90-100 (Q4 holiday period)

  ## 🎛️ Interactive Slicers & Filters

### 📌 Available Slicers

| Slicer | Options | Purpose |
|--------|---------|---------|
| **Product Category** | All, Audio Video, Camera, Car Accessories, Laptop, Men Clothes, Men Shoes, Mobile & Accessories | Filter by product type |
| **Quarter (Qtr)** | All, Q1, Q2, Q3, Q4 | Filter by time period |
| **Order Date** | Date range selector | Custom date filtering |
| **Price Range** | Min-Max slider | Filter by price |
| **Reviews** | 0-100, 100-500, 500-1000, 1000+ | Filter by review count |

---

### 🔄 How They Work

