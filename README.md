# Customer Behavior Analysis – Data Analytics Project

## Overview

This project analyzes customer purchasing behavior using a complete **data analytics workflow**.
The goal is to explore customer trends, clean and prepare the data, perform SQL analysis, and present insights through **interactive dashboards and reports**.

The project demonstrates skills in **data cleaning, exploratory data analysis (EDA), SQL querying, data visualization, and business insight communication**.

---

## Dataset

The dataset contains customer purchase information such as:

* Customer demographics (age, gender, location)
* Products purchased
* Purchase amount
* Review ratings
* Subscription status
* Payment method
* Purchase frequency
* Shipping and discount usage

The data was imported into Python for analysis and later stored in **MySQL** for SQL-based exploration.

---

## Tools & Technologies

The project uses the following tools:

* **Python** – Data loading, cleaning, and EDA
* **Pandas** – Data manipulation and preprocessing
* **MySQL** – SQL queries for data analysis
* **SQLAlchemy** – Connecting Python to MySQL
* **Power BI** – Building an interactive dashboard
* **Microsoft PowerPoint** – Presenting insights
* **Jupyter Notebook** – Running Python analysis

---

## Project Steps

### 1. Data Loading

* Loaded the dataset using **Pandas**
* Inspected structure, column names, and data types

### 2. Exploratory Data Analysis (EDA)

* Analyzed distributions of key variables
* Examined customer demographics
* Identified patterns in purchasing behavior
* Investigated product categories and ratings

### 3. Data Cleaning

* Handled missing values
* Standardized column names
* Created additional variables such as **age groups**
* Verified data consistency

### 4. SQL Analysis

Data was loaded into **MySQL** and analyzed with SQL queries.

Examples of analysis performed:

* Customer spending by subscription status
* Average product ratings
* Top products by category
* Revenue breakdown by gender and category

### 5. Dashboard Development

An interactive **Power BI dashboard** was created to visualize key insights.

Dashboard highlights include:

* Customer demographics overview
* Purchase trends
* Product performance
* Revenue analysis
* Subscription behavior

### 6. Reporting

Insights from the analysis were summarized in:

* **Power BI dashboard**
* **Analytical report**
* **Presentation (PPT)**

These materials communicate key business findings and recommendations.

---

## Dashboard Highlights

The Power BI dashboard includes visualizations such as:

* Customer distribution by age group and gender
* Revenue by product category
* Top-performing products
* Purchase frequency patterns
* Subscription vs non-subscription spending behavior

These visuals help stakeholders quickly understand customer purchasing patterns.

---

## Key Results & Insights

Some insights discovered in the analysis:

* Certain product categories generate significantly higher revenue.
* Subscription customers tend to have higher average spending.
* A few products dominate sales within each category.
* Customer purchase frequency strongly impacts total revenue.

These insights can support **marketing strategies, product planning, and customer retention efforts**.

---

## How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/customer-behavior-analysis.git
cd customer-behavior-analysis
```

### 2. Install Dependencies

```bash
pip install pandas sqlalchemy pymysql
```

### 3. Run Python Analysis

Run the Jupyter Notebook or Python scripts to:

* Load and clean the dataset
* Perform EDA
* Upload data to MySQL

### 4. Run SQL Queries

Use MySQL to execute the analysis queries provided in the project.

### 5. Open the Dashboard

Open the **Power BI file (.pbix)** to explore the interactive dashboard.

### 6. View the Report & Presentation

Review the **report and PowerPoint presentation** for summarized insights.

---

## Project Structure

```
data/
    dataset.csv

notebooks/
    eda_analysis.ipynb

sql/
    analysis_queries.sql

dashboard/
    customer_behavior_dashboard.pbix

report/
    analysis_report.pdf

presentation/
    project_presentation.pptx
```


