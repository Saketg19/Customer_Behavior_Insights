# Customer Shopping Behavior Analysis

## Overview

An end-to-end data analytics project focused on understanding customer purchasing behavior, spending patterns, product preferences, and subscription trends.

The project uses Python for data cleaning and exploratory data analysis (EDA), SQL Server for business analysis, and Power BI for interactive dashboard development. An executive summary report and a Gamma presentation communicate the key findings and business recommendations.

## Dataset

The dataset contains approximately **3,900 records and 18 columns**, covering customer demographics, purchases, product categories, discounts, ratings, and subscription information.

**Key attributes:**
- Customer demographics and age groups
- Purchase amounts and product categories
- Review ratings and discount information
- Subscription status and previous purchases
- Shipping preferences and purchase frequency

## Tools & Technologies

- **Python:** Data analysis and preprocessing
- **Pandas & NumPy:** Data manipulation and cleaning
- **Matplotlib & Seaborn:** Exploratory data visualization
- **SQL Server:** SQL queries and business analysis
- **Power BI:** Interactive dashboards and KPI visualization
- **Jupyter Notebook:** Python analysis
- **Gamma:** Presentation creation

## Project Workflow

### 1. Data Loading

Loaded the raw dataset into Python using Pandas and examined its structure, dimensions, column names, and data types.

### 2. Exploratory Data Analysis (EDA)

Analyzed customer demographics, purchasing patterns, spending behavior, product preferences, and subscription trends to identify meaningful patterns and business opportunities.

### 3. Data Cleaning & Preprocessing

- Identified and handled missing review ratings.
- Standardized column names and data types.
- Created useful features, including customer age groups.
- Removed redundant columns.
- Prepared the cleaned dataset for SQL analysis.

### 4. SQL Analysis

Loaded the prepared data into SQL Server and performed business analysis using:

- Aggregate functions and `GROUP BY`
- Filtering and conditional logic
- Subqueries and Common Table Expressions (CTEs)
- Window functions and ranking
- Revenue and customer-segment analysis

### 5. Power BI Dashboard

Developed an interactive dashboard to visualize key performance indicators, customer segments, sales by category, subscription behavior, and revenue by age group.

### 6. Report & Presentation

Created an executive summary report highlighting analytical findings and business recommendations. Developed a presentation using Gamma to communicate the project outcomes clearly and visually.

## Dashboard

The interactive Power BI dashboard provides an overview of customer shopping behavior and purchasing patterns.

**Key metrics and visualizations:**
- Total number of customers
- Average purchase amount
- Average review rating
- Sales by product category
- Subscription distribution
- Revenue by age group

### Dashboard Preview

![Customer Behavior Dashboard](https://raw.githubusercontent.com/Saketg19/Customer_Behavior_Insights/main/dashboard.png)

[**View Dashboard Screenshot in Full Size**](https://github.com/Saketg19/Customer_Behavior_Insights/blob/main/dashboard.png)

## Results & Insights

The analysis explored several aspects of customer shopping behavior:

- **Customer Segmentation:** Examined loyal, returning, and new customer groups.
- **Subscription Analysis:** Compared subscriber and non-subscriber spending and revenue.
- **Product Performance:** Identified highly rated products and popular categories.
- **Discount Analysis:** Investigated products associated with higher discount rates.
- **Shipping Analysis:** Compared average purchase amounts across shipping methods.
- **Age Group Analysis:** Evaluated revenue distribution across different age groups.

### Business Recommendations

- Encourage subscription adoption through targeted benefits and offers.
- Improve customer retention through loyalty programs.
- Evaluate discount strategies to balance sales and profitability.
- Promote highly rated products and popular categories.
- Develop targeted marketing strategies based on customer segments.

## Project Structure

```text
Customer_Behavior_Insights/
│
├── README.md
├── SQLBusinessQuestions.sql
├── customer_behavior_dashboard.pbix
├── customer_shopping_behavior.csv
├── customer_shopping_behavior.ipynb
└── dashboard.png
```

## How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/Saketg19/Customer_Behavior_Insights.git
cd Customer_Behavior_Insights
```

### 2. Install Python Dependencies

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Run the Python Analysis

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open `customer_shopping_behavior.ipynb` and execute the cells to explore, clean, and analyze the dataset.

### 4. Execute SQL Queries

Open `SQLBusinessQuestions.sql` in SQL Server Management Studio (SSMS), connect to your SQL Server instance, and execute the queries against the prepared database.

Ensure that the required database and tables are available before running the queries.

### 5. Explore the Power BI Dashboard

Open `customer_behavior_dashboard.pbix` in Power BI Desktop. Configure the SQL Server data source and credentials if prompted.

### 6. View the Report & Presentation

Review the executive summary report and Gamma presentation for the key findings, visualizations, and business recommendations. These deliverables can be added to the repository when available.

## Key Takeaway

This project demonstrates an end-to-end data analytics workflow, transforming raw customer shopping data into actionable business insights using Python, SQL Server, and Power BI.

---

**Author:** Saket Gupta

**Domain:** Data Analytics

**Technologies:** Python | SQL Server | Power BI | Pandas | NumPy | Gamma
