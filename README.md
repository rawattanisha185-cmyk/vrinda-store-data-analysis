# 📊 Vrinda Store Data Analysis — 2022

An end-to-end **Microsoft Excel data analysis project** based on Vrinda Store's 2022 sales data. The project analyzes sales performance, customer demographics, order status, product categories, sales channels, and geographic distribution to identify meaningful business insights.

---

## 📌 Project Overview

The objective of this project is to analyze Vrinda Store's sales data and understand:

* Overall sales performance
* Monthly sales trends
* Customer purchasing behavior
* Gender-wise sales performance
* Product/category performance
* Sales channel performance
* Order status and fulfillment
* State-wise sales distribution
* Top-performing states
* Customer age-group behavior

The analysis was performed using **Microsoft Excel**, with supporting pivot tables, formulas, and summarized reports.

---

## 🛠️ Tools & Technologies

* **Microsoft Excel**
* Pivot Tables
* Data Cleaning
* Data Aggregation
* Excel Formulas
* Conditional Analysis
* Data Visualization
* Business Intelligence / Exploratory Data Analysis

---

## 📂 Dataset

The main dataset is stored in the `Vrinda Store` worksheet.

### Dataset Size

* **31,047 records**
* **21 columns**
* **28,471 unique orders**
* **28,437 unique customers**

### Important Columns

| Column           | Description                       |
| ---------------- | --------------------------------- |
| Order ID         | Unique order identifier           |
| Cust ID          | Customer identifier               |
| Gender           | Customer gender                   |
| GENDER GRP       | Customer age-group classification |
| Age              | Customer age                      |
| Date             | Order date                        |
| MONTH            | Order month                       |
| Status           | Order status                      |
| Channel          | Sales channel                     |
| SKU              | Product identifier                |
| Category         | Product category                  |
| Size             | Product size                      |
| Qty              | Quantity ordered                  |
| Amount           | Order amount                      |
| Ship City        | Customer shipping city            |
| Ship State       | Customer shipping state           |
| Ship Postal Code | Customer postal code              |
| Ship Country     | Customer country                  |
| B2B              | Business-to-business indicator    |

---

## 📊 Workbook Structure

The Excel workbook contains multiple analytical worksheets:

### `Vrinda Store`

Contains the primary transactional dataset used for analysis.

### `vrinda store report 2022`

Contains the annual sales report and summarized business analysis.

### `women vs men`

Analyzes sales performance by gender.

### `order staus`

Provides an overview of order fulfillment and order-status distribution.

### `top 5 states`

Identifies the highest-performing states based on sales amount.

### `Sheet1`

Contains monthly sales/order analysis.

### `Sheet6`

Contains gender-wise order analysis.

### `Sheet7`

Contains sales-channel analysis.

---

## 📈 Key Business Metrics

| KPI                 |      Result |
| ------------------- | ----------: |
| Total Sales         | ₹21,176,377 |
| Total Quantity Sold |      31,198 |
| Unique Orders       |      28,471 |
| Unique Customers    |      28,437 |
| Average Order Value |     ₹743.79 |
| Delivered Orders    |      28,641 |
| Returned Orders     |       1,045 |
| Cancelled Orders    |         844 |
| Refunded Orders     |         517 |

> **Note:** Sales amount represents the values available in the provided dataset and may include records with different order statuses.

---

## 🔎 Key Insights

### 1. Category Performance

The **Set** category generated the highest sales amount, followed by:

1. Set
2. Kurta
3. Western Dress
4. Top
5. Saree

This indicates that traditional and coordinated apparel products were major contributors to overall sales.

---

### 2. Sales Channel Performance

The leading sales channels by revenue were:

| Channel  |      Sales |
| -------- | ---------: |
| Amazon   | ₹7,519,933 |
| Myntra   | ₹4,941,540 |
| Flipkart | ₹4,573,301 |
| Ajio     | ₹1,331,427 |
| Nalli    | ₹1,015,329 |
| Meesho   |   ₹927,606 |
| Others   |   ₹867,241 |

**Amazon** was the strongest sales channel in the dataset.

---

### 3. Top Performing States

The highest-revenue states were:

| Rank | State         |      Sales |
| ---: | ------------- | ---------: |
|    1 | Maharashtra   | ₹2,990,221 |
|    2 | Karnataka     | ₹2,646,358 |
|    3 | Uttar Pradesh | ₹2,104,659 |
|    4 | Telangana     | ₹1,712,439 |
|    5 | Tamil Nadu    | ₹1,678,877 |

**Maharashtra** generated the highest sales among the states in the dataset.

---

### 4. Gender Analysis

The dataset contains a larger number of female customer/order records than male records.

* Female records: **21,553**
* Male records: **9,494**

The analysis therefore indicates a strong female customer presence in Vrinda Store's sales data.

---

### 5. Order Status

The dataset contains four major order statuses:

* Delivered
* Returned
* Cancelled
* Refunded

Delivered orders represent the largest portion of the recorded transactions, while returns, cancellations, and refunds provide useful indicators for evaluating order fulfillment and customer experience.

---

## 📅 Monthly Sales Analysis

The workbook also contains monthly sales analysis for 2022.

Monthly revenue was analyzed to identify:

* Peak sales months
* Lower-performing months
* Seasonal patterns
* Changes in customer purchasing activity

This can help the business plan inventory, promotions, and marketing campaigns more effectively.

---

## 💡 Business Recommendations

Based on the analysis, the following strategies could be considered:

### 1. Focus on High-Performing Categories

Increase inventory and promotional activity for high-performing categories such as **Set, Kurta, and Western Dress**.

### 2. Strengthen Major Sales Channels

Amazon, Myntra, and Flipkart contribute significantly to sales. Maintaining strong visibility and promotions across these channels could help sustain revenue.

### 3. Target High-Revenue States

Maharashtra, Karnataka, Uttar Pradesh, Telangana, and Tamil Nadu show strong sales performance and could receive targeted regional marketing campaigns.

### 4. Analyze Returns and Cancellations

Returns and cancellations should be monitored to identify possible issues with:

* Product quality
* Product descriptions
* Sizing
* Delivery experience
* Customer expectations

### 5. Use Customer Segmentation

Age and gender information can be used to create more targeted campaigns and personalized product recommendations.

---

## 📁 Repository Structure

```text
Vrinda-Store-Data-Analysis/
│
├── Vrinda Store Data Analysis.xlsx
└── README.md
```

---

## 🚀 How to Use

1. Download the Excel workbook.
2. Open it using Microsoft Excel.
3. Navigate through the individual worksheets.
4. Start with the `vrinda store report 2022` worksheet for the summarized analysis.
5. Use the `Vrinda Store` worksheet to explore the underlying transactional data.

---

## 📌 Project Highlights

* 31K+ transactional records analyzed
* 28K+ unique orders
* 28K+ unique customers
* ₹2.11 Cr+ sales value
* Monthly sales analysis
* Gender-based analysis
* Category performance analysis
* Sales-channel analysis
* State-wise analysis
* Order-status analysis
* Excel-based business reporting

---

## 👨‍💻 Author

**Tanisha Rawat**

This project was created as part of my **Data Analytics / Excel portfolio** to demonstrate practical skills in data cleaning, analysis, reporting, and extracting business insights from real-world sales data.

---

⭐ If you found this project useful, consider giving the repository a star!
#   v r i n d a - s t o r e - d a t a - a n a l y s i s  
 