
# Customer Behavior Analysis Dashboard

## 1. Project Overview

This project analyzes customer shopping behavior to understand purchasing patterns, revenue, product preferences, customer loyalty, discounts, and subscription trends.

The project follows an end-to-end data analytics workflow using Python, MySQL, SQL, and Power BI to convert raw data into meaningful business insights.

## 2. Project Objectives

- Analyze customer shopping behavior.
- Clean and prepare data using Python.
- Perform Exploratory Data Analysis (EDA).
- Analyze business questions using SQL.
- Create an interactive Power BI dashboard.
- Generate a project report and presentation using Gamma AI.
- Provide business insights and recommendations.

## 3. Dataset

- Dataset Name: Customer Shopping Behavior
- Total Records: 3,900
- Original Columns: 18
- Data Format: CSV
- Data Includes:
  - Customer ID, Age, and Gender
  - Products and Categories
  - Purchase Amount
  - Review Ratings
  - Subscription Status
  - Shipping Type
  - Discounts and Promo Codes
  - Payment Method
  - Previous Purchases
  - Purchase Frequency

## 4. Tools and Technologies

- Python
- Pandas
- Jupyter Notebook
- MySQL Server
- MySQL Workbench
- SQL
- SQLAlchemy
- PyMySQL
- Power BI
- Gamma AI
- GitHub

## 5. Project Workflow

### Step 1: Data Loading
- Imported the CSV dataset using Python and Pandas.
- Checked the dataset structure, columns, and data types.

### Step 2: Exploratory Data Analysis (EDA)
- Analyzed customer demographics and purchasing patterns.
- Examined revenue, product categories, ratings, and discounts.
- Identified missing values and important trends.

### Step 3: Data Cleaning
- Standardized column names.
- Handled missing review ratings using category-level median values.
- Created age groups.
- Converted purchase frequency into approximate days.
- Prepared the dataset for analysis.

### Step 4: SQL Analysis
- Loaded the cleaned dataset into MySQL Server.
- Created the customer_behavior database.
- Stored the data in the customer table.
- Executed 10 SQL queries to answer business questions.

SQL concepts used:
- SELECT and WHERE
- GROUP BY and ORDER BY
- Aggregate Functions
- CASE Statements
- Subqueries
- Common Table Expressions (CTEs)
- Window Functions

### Step 5: Power BI Dashboard
- Connected Power BI to the MySQL database.
- Created KPI cards and charts.
- Added interactive slicers and filters.
- Visualized customer behavior, revenue, and product categories.

### Step 6: Report and Presentation
- Prepared project documentation.
- Summarized key findings and recommendations.
- Created a presentation using Gamma AI.

## 6. Power BI Dashboard

The dashboard includes the following KPIs:

- Number of Customers
- Average Purchase Amount
- Average Review Rating

### Dashboard Visualizations

- Customers by Subscription Status
- Sales by Age Group
- Revenue by Age Group
- Revenue by Product Category
- Sales by Product Category

### Interactive Filters

- Subscription Status
- Gender
- Category
- Shipping Type


## 7. Key Results

The analysis produced the following results:

- Total Revenue: Approximately $233,081
- Average Purchase Amount: Approximately $59.76
- Average Review Rating: Approximately 3.75
- Total Customer Records: 3,900

### Key Business Insights

- Male customers generated approximately 68% of total revenue.
- Clothing was the highest revenue-generating category, contributing approximately $104,264.
- Accessories generated approximately $74,200 in revenue.
- Approximately 27% of customers had a subscription.
- Loyal customers represented the largest customer segment.
- Express shipping customers spent slightly more on average than Standard shipping customers.
- Young Adults generated the highest revenue among the four age groups.

## 8. Business Recommendations

- Encourage loyal customers to subscribe through targeted offers.
- Review discount strategies for frequently discounted products.
- Improve customer engagement among under-represented customer groups.
- Focus marketing efforts on high-revenue categories.
- Promote highly rated products to improve customer engagement.

## 9. Project Structure

customer-behavior-analysis/
|
|-- data/
|   |-- customer_shopping_behavior.csv
|
|-- notebooks/
|   |-- customer_shopping_behavior.ipynb
|
|-- sql/
|   |-- customer_behavior_analysis_dashboard.sql
|
|-- dashboard/
|   |-- customer_behavior_analysis_dashboard.pbix
|
|-- report/
|   |-- project_documentation.pdf
|
|-- presentation/
|   |-- project_presentation.pdf
|
|-- images/
|   |-- dashboard.png
|
|-- README.md

Note: Adjust folder and file names to match your actual GitHub repository.

## 10. How to Run the Project

### Requirements

- Python 3.x
- MySQL Server
- MySQL Workbench
- Power BI Desktop
- Jupyter Notebook

### Step 1: Install Python Libraries

Run the following command:

pip install pandas sqlalchemy pymysql jupyter

### Step 2: Create the Database

Open MySQL Workbench and execute:

CREATE DATABASE customer_behavior;

### Step 3: Run the Python Notebook

- Open the Jupyter Notebook.
- Configure your MySQL connection securely.
- Run the notebook cells in order.
- Load the cleaned dataset into the customer table.

### Step 4: Execute SQL Queries

- Open the SQL file in MySQL Workbench.
- Select the customer_behavior database.
- Execute the queries and review the results.

### Step 5: Open the Power BI Dashboard

- Open the PBIX file in Power BI Desktop.
- Configure the MySQL connection.
- Refresh the data.
- Explore the dashboard using filters and slicers.

### Step 6: Review the Report and Presentation

Open the project documentation and Gamma presentation to review the analysis, results, and recommendations.

## 11. Skills Demonstrated

- Data Cleaning and Preprocessing
- Exploratory Data Analysis (EDA)
- Python and Pandas
- SQL Querying
- MySQL Database Management
- Power BI Dashboard Development
- Data Visualization
- Business Analysis
- Reporting and Data Storytelling

## 12. Author

Ravi  Pawar
Aspiring Data Analyst

Skills: Python | SQL | MySQL | Power BI | Excel

LinkedIn: https://linkedin.com/in/ravi-pawar-4b385a248

GitHub: https://github.com/pawarravi997

---

This project demonstrates the complete data analytics process, from raw data preparation to SQL analysis, interactive dashboards, and business recommendations.
