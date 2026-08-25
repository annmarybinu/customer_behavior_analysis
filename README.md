# Customer Shopping Behavior Analysis

## Overview

This project is an end-to-end Data Analytics solution designed to analyze customer shopping behavior and uncover actionable business insights. The analysis combines Python, PostgreSQL, SQL, and Power BI to transform raw transactional data into meaningful recommendations for improving customer engagement, marketing effectiveness, and revenue growth.

The project follows the complete analytics lifecycle, including data cleaning, exploratory data analysis (EDA), database integration, SQL-based business analysis, dashboard development, and stakeholder reporting.

---

## Business Problem

A retail company wants to better understand customer purchasing behavior across demographics, product categories, subscription status, and shopping preferences. The goal is to identify trends, improve customer loyalty, optimize marketing strategies, and support data-driven decision-making.

---

## Dataset

The dataset contains customer shopping transactions and behavioral information.

### Dataset Information

* Records: 3,900 customer purchases
* Features: 18 columns
* Customer demographics
* Product and purchase details
* Subscription information
* Discount and promotion usage
* Review ratings and shipping preferences

### Key Variables

* Age
* Gender
* Location
* Subscription Status
* Product Category
* Purchase Amount
* Season
* Discount Applied
* Review Rating
* Shipping Type
* Purchase Frequency

---

## Tools & Technologies

| Tool                 | Purpose                                |
| -------------------- | -------------------------------------- |
| Python               | Data cleaning, transformation, and EDA |
| Pandas               | Data manipulation                      |
| NumPy                | Numerical operations                   |
| Matplotlib & Seaborn | Data visualization                     |
| PostgreSQL           | Data storage and analysis              |
| SQL                  | Business query analysis                |
| SQLAlchemy           | Python–PostgreSQL integration          |
| Power BI             | Interactive dashboard creation         |
| Gamma                | Presentation design                    |
| GitHub               | Project version control                |

---

## Project Workflow

### 1. Data Preparation (Python)

* Loaded and explored the dataset using Pandas
* Performed descriptive analysis and data validation
* Handled missing values in review ratings
* Standardized column names using snake_case
* Created new features such as age groups
* Removed redundant fields
* Prepared a clean dataset for database analysis

### 2. Exploratory Data Analysis (EDA)

* Examined customer demographics
* Analyzed spending patterns
* Evaluated subscription behavior
* Investigated discount usage trends
* Identified product preferences
* Explored purchase frequency and customer segments

### 3. Database Integration (PostgreSQL)

* Connected Python to PostgreSQL
* Imported cleaned data into relational tables
* Prepared the dataset for SQL-based business analysis

### 4. SQL Business Analysis

Key business questions answered include:

* Revenue by gender
* Subscriber vs non-subscriber performance
* High-spending discount users
* Top-rated products
* Shipping type comparisons
* Customer segmentation
* Revenue contribution by age group
* Repeat buyer behavior
* Top products within each category

### 5. Power BI Dashboard

Built an interactive dashboard to help stakeholders monitor business performance and customer behavior through visual analytics.

---

## Dashboard Features

The Power BI dashboard includes:

* Total Revenue KPI
* Customer Demographics Analysis
* Revenue by Gender
* Revenue by Age Group
* Subscription Performance
* Product Category Insights
* Top Products Analysis
* Shipping Preference Analysis
* Customer Segmentation Overview

### Interactive Elements

* Filters and slicers
* Drill-down functionality
* Dynamic KPI tracking
* Trend analysis visualizations

---

## Key Insights

The analysis revealed:

* Customer purchasing patterns across demographic groups
* Revenue differences between subscribers and non-subscribers
* Top-performing products and categories
* Impact of discounts on customer spending
* Characteristics of loyal and repeat customers
* High-value customer segments for targeted marketing

---

## Business Recommendations

* Increase subscription adoption through exclusive benefits
* Strengthen customer loyalty programs
* Optimize discount strategies to balance revenue and profitability
* Promote top-rated products in marketing campaigns
* Focus targeted marketing on high-value customer segments
---

## How to Run

### 1. Clone the Repository

```bash
git clone <repository-url>
```

### 2. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2
```

### 3. Run Python Analysis

Open and execute:

```text
customer_behavior_analysis.ipynb
```

### 4. Load Data into PostgreSQL

* Create a PostgreSQL database
* Execute the database connection script
* Import the cleaned dataset

### 5. Run SQL Queries

Execute:

```sql
customer_behavior_analysis.sql
```

### 6. Open Power BI Dashboard

Launch the `.pbix` file and refresh the data source connection if required.

---

## Project Deliverables

* Python Notebook for EDA and Data Cleaning
* PostgreSQL Database Integration
* SQL Query Scripts
* Power BI Dashboard
* Project Report
* Gamma Presentation
* GitHub Repository

---

## Conclusion

This project demonstrates practical skills in data cleaning, exploratory analysis, SQL querying, dashboard development, and business storytelling. By combining Python, PostgreSQL, SQL, and Power BI, the project converts raw customer transaction data into actionable business insights that support strategic decision-making.
