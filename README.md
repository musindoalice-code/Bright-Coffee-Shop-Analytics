# Bright-Coffee-Shop-Analytics
This project analyses Bright Coffee Shop's transactional sales data to transform raw business data into actionable insights for executive decision-making
# ☕ Bright Coffee Shop | CEO Sales & Performance Analytics

## 📊 Executive Dashboard & Business Intelligence Project

### 🔗 Project Overview

This project analyses **Bright Coffee Shop's transactional sales data** to transform raw business data into actionable insights for executive decision-making.

The objective was to answer key CEO-level business questions around **revenue performance, product demand, store performance, customer purchasing behaviour, and operational peak periods**.

Using Excel, data analysis techniques, and interactive dashboard design, I developed a CEO-focused reporting solution that tells a clear business story:

> **Performance → Growth → Business Drivers → Action**

---

## 🎯 Business Objective

The CEO needs a clear understanding of the company's performance and the key factors driving revenue growth.

This analysis focuses on answering the following questions:

* 💰 How much revenue is the business generating?
* 📈 How is revenue changing over time?
* 🏪 Which stores are performing best?
* ☕ Which products and categories generate the most revenue?
* 🕒 When are customers most likely to make purchases?
* 📦 What operational opportunities can improve sales and efficiency?

The final output is an interactive CEO dashboard designed to support faster and more informed business decisions.

---

# 📁 Project Structure

```text
Bright-Coffee-Shop-CEO-Analytics/
│
├── 📊 Bright_Coffee_CEO_Dashboard.xlsx
│
├── 📁 Data/
│   └── Bright Coffee transactional dataset
│
├── 📁 Dashboard/
│   ├── Executive Overview
│   ├── Product Performance
│   └── Time & Operations
│
├── 📁 Images/
│   └── Dashboard screenshots
│
├── 📁 SQL/
│   └── SQL queries and business analysis
│
└── README.md
```

---

# 📂 Dataset Overview

The dataset contains transactional sales information from Bright Coffee Shop.

### Dataset Size

* **149,116 transactions**
* **15 analytical fields**
* **3 store locations**
* **29 product types**
* **6 months of sales data**
* **Period:** January 2023 – June 2023

### Key Columns

| Column                   | Description                            |
| ------------------------ | -------------------------------------- |
| `transaction_id`         | Unique identifier for each transaction |
| `date`                   | Transaction date                       |
| `month`                  | Transaction month                      |
| `month_name`             | Month name                             |
| `day_name`               | Day of the week                        |
| `store`                  | Coffee shop location                   |
| `product_type`           | Product purchased                      |
| `units_sold`             | Quantity sold                          |
| `revenue`                | Revenue generated                      |
| `hour`                   | Hour of transaction                    |
| `minute`                 | Minute of transaction                  |
| `thirty_minute_interval` | 30-minute purchasing interval          |
| `category`               | Product category                       |
| `store_hour`             | Combined store and hour dimension      |
| `category_hour`          | Combined category and hour dimension   |

---

# 🛠️ Tools & Skills Demonstrated

This project demonstrates practical data analyst skills across the complete analytics workflow.

### 📊 Microsoft Excel

* Data cleaning and preparation
* Data validation
* Pivot tables
* Pivot charts
* KPI calculations
* Interactive dashboard development
* Business storytelling

### 📈 Data Analytics

* Exploratory Data Analysis (EDA)
* Revenue analysis
* Trend analysis
* Product performance analysis
* Store performance comparison
* Time-based analysis
* Business recommendations

### 🧠 Business Intelligence

The dashboard was designed specifically for executive decision-making rather than simply displaying charts. Each dashboard page answers a specific business question.

---

# 📊 Dashboard Structure

## 1️⃣ Executive Overview

The Executive Overview provides a high-level view of overall business performance.

Key areas include:

* Total Revenue
* Total Units Sold
* Revenue Growth
* Store Performance
* Monthly Revenue Trends
* Key Performance Indicators (KPIs)

🎯 **Business Question:**

> How is the business performing overall, and where should management focus?

---

## 2️⃣ Product Performance

This dashboard investigates the products and categories driving business performance.

Key analysis areas include:

* Revenue by Product Category
* Product Performance
* Units Sold
* Revenue versus Volume
* Category Performance by Month

🎯 **Business Question:**

> Which products generate the most value, and which products drive customer demand?

---

## 3️⃣ Time & Operations

This dashboard focuses on customer purchasing behaviour and operational demand.

Key analysis areas include:

* Sales by Hour
* Peak Purchasing Windows
* Slow Periods
* Customer Demand Patterns
* Operational Opportunities

🎯 **Business Question:**

> When do customers buy, and how can the business optimise staffing and inventory?

---

# 💡 Key Business Insights

## 💰 Strong Overall Revenue Performance

Bright Coffee generated approximately **$698.8K in total revenue** from more than **214K units sold** during the six-month analysis period.

This demonstrates a high transaction volume and provides a strong foundation for analysing the drivers of business growth.

---

## 📈 Revenue Increased Significantly Over Time

Revenue performance showed a strong upward trend across the analysis period.

The strongest month was **June**, generating approximately **$166.5K in revenue**, compared with approximately **$76.1K in February**, the lowest-performing month.

### 📌 Business Implication

Management should investigate the factors behind the significant growth in the later months and identify whether the increase was driven by:

* Higher customer traffic
* Seasonal demand
* Product mix
* Marketing activity
* Store performance

Understanding these drivers can help the business replicate successful strategies.

---

## 🏪 Store Performance Is Relatively Balanced

The three store locations generated relatively similar levels of revenue:

* **Hell's Kitchen:** ~$236.5K
* **Astoria:** ~$232.2K
* **Lower Manhattan:** ~$230.1K

### 📌 Business Implication

No single store is overwhelmingly responsible for company performance. This indicates a relatively balanced store portfolio.

However, Hell's Kitchen represents the strongest opportunity to study successful operating practices and potentially apply them across other locations.

---

## ☕ Coffee Is the Largest Revenue Driver

Coffee generated approximately **$275.5K in revenue**, making it the strongest-performing category.

Tea was the second-largest category, generating approximately **$207.6K**.

### 📌 Business Implication

Coffee and Tea should remain strategic priorities for:

* Inventory management
* Product availability
* Marketing campaigns
* Upselling opportunities
* Customer loyalty initiatives

---

## 🕒 Morning Hours Are the Most Important Sales Window

Customer purchasing activity is strongest during the morning period.

The highest revenue-generating hours include:

* **10:00**
* **09:00**
* **08:00**

### 📌 Business Implication

Morning operations are critical to business success. Management should ensure:

* Adequate staffing during peak hours
* High product availability
* Fast service and queue management
* Sufficient inventory before peak demand begins

---

# 🚀 Strategic Recommendations

Based on the analysis, I recommend the following actions:

### 1. Optimise Morning Operations

Increase staffing and product availability during the morning peak period to improve customer experience and reduce potential lost sales.

### 2. Focus Marketing on High-Value Categories

Develop promotions and loyalty campaigns around Coffee and Tea, the company's strongest revenue-generating categories.

### 3. Replicate Best Practices Across Stores

Analyse the operating model of Hell's Kitchen and identify practices that can be applied to Astoria and Lower Manhattan.

### 4. Investigate Revenue Growth Drivers

Conduct deeper analysis into the strong revenue growth between February and June to determine what caused the improvement.

### 5. Create Upselling Opportunities

Use high-traffic periods to promote complementary products, such as food items or premium beverages.

---

# 📈 CEO Dashboard Storytelling Framework

The dashboard follows a structured executive storytelling approach:

```text
        ┌─────────────────────┐
        │   BUSINESS PULSE    │
        │ Revenue • Units • KPIs
        └──────────┬──────────┘
                   │
                   ▼
        ┌─────────────────────┐
        │       GROWTH        │
        │ Monthly Trends      │
        └──────────┬──────────┘
                   │
                   ▼
        ┌─────────────────────┐
        │  BUSINESS DRIVERS   │
        │ Stores • Products   │
        └──────────┬──────────┘
                   │
                   ▼
        ┌─────────────────────┐
        │      ACTION         │
        │ Operations • Strategy
        └─────────────────────┘
```

This approach ensures that the dashboard does not simply describe what happened—it helps leadership understand **why it happened and what to do next**.

---

# 📸 Dashboard Preview

> 📌 Add screenshots of your Excel dashboard to the `/Images` folder and link them below.

### Executive Overview

![Executive Dashboard](Images/executive-overview.png)

### Product Performance

![Product Performance](Images/product-performance.png)

### Time & Operations

![Time and Operations](Images/time-operations.png)

---

# 📌 Key KPIs

| KPI                 | Business Purpose                       |
| ------------------- | -------------------------------------- |
| Total Revenue       | Measures overall financial performance |
| Total Units Sold    | Measures sales volume                  |
| Revenue by Store    | Compares location performance          |
| Revenue by Category | Identifies key business drivers        |
| Monthly Revenue     | Tracks growth trends                   |
| Revenue by Hour     | Identifies peak operational periods    |

---

# 🔍 Analytical Approach

The project followed a structured analytics workflow:

### 1. Understand the Business Problem

Identify the questions and decisions the CEO needs to make.

### 2. Explore the Data

Review the dataset structure, transaction volume, dates, stores, products, and potential data quality issues.

### 3. Prepare the Data

Create analytical fields and ensure the data is ready for reporting.

### 4. Analyse Business Performance

Investigate revenue, sales volume, products, stores, and customer purchasing patterns.

### 5. Build the Dashboard

Design an executive-friendly dashboard with clear KPIs and meaningful visualisations.

### 6. Generate Recommendations

Translate analytical findings into practical business actions.

---

# 🧠 What I Learned

Through this project, I strengthened my ability to:

* Translate business questions into analytical questions
* Work with large transactional datasets
* Identify meaningful KPIs
* Design dashboards for executive audiences
* Transform raw data into business insights
* Communicate recommendations using data storytelling

---

# 🚀 Future Improvements

Future versions of this project could include:

* SQL-based data analysis
* Power BI dashboard development
* Automated data refreshes
* Profit and margin analysis
* Customer segmentation
* Sales forecasting
* Store-level benchmarking
* Machine learning demand forecasting

---

# 👩‍💻 Author

**Data Analyst Portfolio Project**

This project was created as part of my practical Data Analytics portfolio to demonstrate my ability to analyse business data, develop dashboards, and communicate insights to decision-makers.

### 📫 Connect With Me

* **GitHub:** Add your GitHub profile link here
* **LinkedIn:** Add your LinkedIn profile link here

---

# ⭐ If You Like This Project

If you found this project interesting, please consider giving the repository a ⭐.

Feedback and collaboration are always welcome!
