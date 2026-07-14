# Customer Shopping Behavior Analysis

An end-to-end **data analytics project** focused on understanding customer shopping behavior for a retail business.  
The project starts from a clearly defined business problem and follows the full analytics workflow: 

**Python data preparation → PostgreSQL/SQL analysis → Power BI dashboard → business recommendations**.

---

## Project Overview

Retail businesses collect large amounts of customer and transaction data, but the value comes from turning that data into useful business decisions. In this project, I analyzed customer shopping behavior to identify trends in revenue, product categories, subscription status, shipping preferences, age groups, and customer loyalty.

The final output is an interactive **Power BI dashboard** that helps stakeholders understand customer behavior and make better marketing, loyalty, and product strategy decisions.

---

## Business Problem

A retail company wants to better understand its customers’ shopping behavior in order to improve sales, customer satisfaction, and long-term loyalty.

**Main business question:**

> How can the company leverage consumer shopping data to identify trends, improve customer engagement, and optimize marketing and product strategies?

---

## Dataset Summary

The dataset contains customer shopping transaction records.

| Item | Details |
|---|---|
| Total records | 3,900 transactions |
| Total columns | 18 features |
| Customer information | Age, Gender, Location, Subscription Status |
| Purchase information | Item Purchased, Category, Purchase Amount, Season, Size, Color |
| Behavioral information | Discount Applied, Promo Code Used, Previous Purchases, Frequency of Purchases, Review Rating, Shipping Type |
| Missing values handled | Review Rating column |

---

## Tools & Technologies

- **Python** - data cleaning, preprocessing, feature engineering, and EDA
- **Pandas** - data manipulation
- **PostgreSQL** - database storage and SQL analysis
- **SQL** - business query development
- **Power BI** - dashboard design and visualization
- **GitHub** - project documentation and version control

---

## Project Workflow

```text
Business Problem Definition
        ↓
Data Cleaning & EDA in Python
        ↓
Feature Engineering
        ↓
Load Cleaned Data into PostgreSQL
        ↓
SQL Business Analysis
        ↓
Power BI Dashboard Development
        ↓
Business Insights & Recommendations
```

---

## Data Preparation in Python

The dataset was cleaned and prepared using Python before moving into SQL and Power BI.

Key steps included:

- Loaded and explored the dataset using `pandas`.
- Checked data structure, summary statistics, and missing values.
- Handled missing values in the `Review Rating` column.
- Standardized column names for better readability.
- Created an **Age Group** feature for customer demographic analysis.
- Created a **Customer Segment** feature based on previous purchases.
- Checked consistency between discount-related columns.
- Loaded the cleaned dataset into PostgreSQL for SQL-based analysis.

---

## SQL Business Analysis

SQL queries were written in PostgreSQL to answer key business questions.

The analysis covered:

- Revenue by gender and age group
- High-spending customers who used discounts
- Top-rated products
- Standard vs. Express shipping comparison
- Subscribers vs. non-subscribers spending behavior
- Products with the highest discount usage
- Customer segmentation into **New**, **Returning**, and **Loyal** customers
- Top 3 most purchased products within each category
- Repeat buyer and subscription behavior
- Revenue contribution by age group

---

## Power BI Dashboard

The Power BI dashboard was designed to present the analysis in a clean and business-friendly way.

Dashboard sections include:

- KPI cards for total customers, total revenue, average purchase amount, average review rating, and subscription rate
- Revenue by product category
- Customer distribution by subscription status
- Revenue contribution by age group
- Average purchase amount by category
- Shipping type analysis
- Customer segmentation overview
- Interactive filters for subscription status, gender, category, shipping type, and age group

### Dashboard Preview

Add your dashboard screenshot here after uploading it to the repository:

```markdown
![Customer Shopping Behavior Dashboard](images/dashboard-preview.png)
```

---

## Key Insights & Recommendations

Based on the analysis, the project suggests the following business actions:

- **Improve customer loyalty:** Returning and loyal customers should be targeted with retention-focused campaigns.
- **Boost subscription adoption:** Subscription benefits can be promoted to customers with strong repeat-purchase behavior.
- **Review discount strategy:** Products with high discount dependency should be monitored to protect profit margins.
- **Promote strong categories:** High-revenue and high-performing product categories can be prioritized in marketing campaigns.
- **Use targeted marketing:** Customer segments and age groups can be used to design more personalized campaigns.

---

## Repository Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── Business Problem Document.pdf
├── Customer Shopping Behavior Analysis.pdf
├── Customer-Shopping-Behavior-Analysis.pptx
├── Customer_Shopping_Behavior_Analysis.ipynb
├── customer_behavior_dashboard.pbix
├── customer_behavior_sql_queries.sql
├── customer_shopping_behavior.csv
├── README.md
└── LICENSE
```

---

## How to Run This Project

### 1. Clone the repository

```bash
git clone https://github.com/your-username/customer-shopping-behavior-analysis.git
cd customer-shopping-behavior-analysis
```

### 2. Install required Python libraries

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2
```

### 3. Run the Jupyter Notebook

Open and run:

```text
Customer_Shopping_Behavior_Analysis.ipynb
```

This notebook handles data loading, cleaning, feature engineering, and database preparation.

### 4. Run SQL queries

Set up a PostgreSQL database and run the SQL script:

```text
customer_behavior_sql_queries.sql
```

### 5. Open the Power BI dashboard

Open the Power BI file:

```text
customer_behavior_dashboard.pbix
```

Refresh the data source if needed and explore the dashboard using the available filters.

---

## Skills Demonstrated

- Business problem understanding
- Data cleaning and preprocessing
- Exploratory data analysis
- Feature engineering
- SQL business analysis
- PostgreSQL database integration
- Power BI dashboard design
- KPI creation and data visualization
- Customer segmentation
- Data storytelling and business recommendations
- GitHub project documentation

---

## Author

**Nethmi Nimasha**  
Data Science Undergraduate  
GitHub: [Nethmi28](https://github.com/Nethmi28)  
LinkedIn: [Nethmi Nimasha](https://www.linkedin.com/in/nethmi-nimasha-/)

---


This project is licensed under the terms included in the repository license file.
