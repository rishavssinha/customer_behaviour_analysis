
# 🛍️ Customer Shopping Behavior Analysis

## 📘 Overview
This project analyzes **customer shopping behavior** using transactional data to uncover insights about spending patterns, product preferences, and subscription trends.
It demonstrates the complete **data analytics lifecycle** — from loading and cleaning data to running SQL queries, building Power BI dashboards, and preparing business recommendations.

---

## 📊 Dataset

**File:** `customer_shopping_behavior.csv`
**Rows:** 3,900  **Columns:** 18

**Key Features**

* **Demographics:** Age, Gender, Location, Subscription Status
* **Purchase Details:** Item Purchased, Category, Purchase Amount, Season, Size, Color
* **Shopping Behavior:** Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type

**Missing Data:** 37 missing values in `Review Rating` were imputed using the median rating of each product category.

---

## 🧰 Tools & Technologies

| Purpose                 | Tools                      |
| ----------------------- | -------------------------- |
| Data Loading & Cleaning | Python (`pandas`, `numpy`) |
| Visualization & EDA     | `matplotlib`, `seaborn`    |
| Database & Queries      | MySQL                      |
| Dashboard               | Power BI                   |
| Reporting               | Word / PowerPoint          |

---

## ⚙️ Project Workflow

### 1️⃣ Data Preparation & Cleaning (Python)

* Loaded dataset using `pandas`
* Performed `.info()` and `.describe()` checks
* Handled missing values and standardized column names
* Created new derived features:

  * `age_group` (binned age intervals)
  * `customer_type` (based on purchase frequency)

### 2️⃣ Exploratory Data Analysis (EDA)

* Explored patterns in **purchase amount, category, season, and location**
* Identified trends across **gender, age group, and subscription status**
* Visualized data distribution, correlations, and outliers

### 3️⃣ SQL Analysis (MySQL)

Performed structured analysis to answer key business questions:

* Revenue by gender and category
* Top 5 locations by average purchase amount
* Shipping type vs. average purchase
* High-spending discount users
* Repeat buyers vs. subscription rate
* Top products by review rating

### 4️⃣ Power BI Dashboard

Built an interactive Power BI dashboard showing:

* Total revenue and purchase trends
* Revenue by gender, location, and category
* Average review ratings and discount impact
* Subscription vs. non-subscription analysis
* Seasonal and shipping insights

### 5️⃣ Business Reporting

Compiled visual insights and recommendations:

* Promote exclusive benefits for subscribers
* Reward loyal repeat buyers through targeted campaigns
* Optimize discount policy to maintain profitability
* Focus marketing efforts on high-revenue demographics

---

## 📈 Results & Insights

* **Top Spending Categories:** Clothing, Footwear, Accessories
* **Subscribers** spend ~25% more than non-subscribers
* **Express Shipping** users have higher purchase values
* **Top-rated products** contribute most to repeat purchases

---

## ▶️ How to Run

### Prerequisites

* Python 3.x
* MySQL 8.x
* Power BI Desktop

### Steps

1. Install dependencies:

   ```bash
   pip install pandas matplotlib seaborn mysql-connector-python
   ```
2. Run the Python notebook/script for EDA and data cleaning.
3. Load the cleaned data into MySQL and execute the SQL scripts.
4. Open the Power BI file (`Customer_Shopping_Behavior.pbix`) to explore the dashboard.


---

⭐ **If you found this project insightful, give it a star!**

