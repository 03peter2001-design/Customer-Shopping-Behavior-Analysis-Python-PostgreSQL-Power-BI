📊 Customer Shopping Behavior Analysis

Analyze customer transactions to uncover spending patterns, product preferences, and subscription behavior. This project demonstrates an end-to-end analytics workflow from data loading to business insights and visualization.

📌 Overview

This project explores customer shopping behavior using Python, SQL, and Power BI. It covers the full analytics pipeline:

Load and explore raw data

Clean and transform datasets

Run SQL queries to extract insights

Build an interactive Power BI dashboard

Summarize findings in a report and presentation

The goal is to translate raw transaction data into actionable insights for business decision-making.

📁 Dataset
Property	Details
Records	3,900 transactions
Features	18 columns
Key Fields	Age, Gender, Purchase Amount, Category, Season, Subscription Status, Payment Method, Review Rating
Source	Internal / Simulated Retail Data
🛠️ Tools & Technologies
Layer	Tools
Programming	Python 3.x
Libraries	Pandas, NumPy, Matplotlib, Seaborn, SQLAlchemy
Database	PostgreSQL / MySQL / SQL Server
Visualization	Power BI
Report	Microsoft Word / Google Docs
Presentation	Gamma
Version Control	Git & GitHub
🔄 Project Steps
1. Data Loading & Exploration (Python)

Load dataset using pandas

Check data types, missing values, and duplicates

Visualize distributions and relationships with matplotlib and seaborn

2. Data Cleaning (Python)

Handle missing values and duplicates

Standardize column names and categories

Convert data types for analysis

Export cleaned dataset for SQL ingestion

3. SQL Analysis (PostgreSQL / MySQL / SQL Server)

Import cleaned dataset into the database

Run queries to answer business questions:

Top revenue-generating product categories

Differences between subscribed vs. non-subscribed customers

Seasonal trends and location-based performance

Average review ratings by category and payment method

4. Power BI Dashboard

Connect Power BI to the database

Create interactive visuals: bar charts, slicers, KPI cards, maps

Enable filtering by gender, age, season, category, and subscription status

5. Written Report

Summarize methodology, findings, and business recommendations

Present insights for both technical and non-technical audiences

6. Presentation (Gamma)

Visual slide deck highlighting key insights, dashboard walkthrough, and recommendations

📊 Dashboard Preview

Screenshot or image of the Power BI dashboard

Key Dashboard Features:

Total Revenue, Average Order Value, and Subscription Rate KPIs

Revenue by Category, Gender, and Season

Customer segmentation by Age Group

Comparison of subscribed vs. non-subscribed customers

💡 Key Results

Top Category: Clothing generated 35% of total revenue

Subscription Impact: Subscribed customers spent 27% more per transaction

Peak Season: Fall had the highest sales volume

Preferred Payment: Credit Card was most common

Ratings Insight: Accessories had the highest average review rating

🚀 How to Run
Prerequisites
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2
Step 1 — Python Notebooks
# Clone repository
git clone https://github.com/your-username/shopping-behavior-analysis.git
cd shopping-behavior-analysis

# Open notebooks in order
jupyter notebook notebooks/01_EDA.ipynb
jupyter notebook notebooks/02_data_cleaning.ipynb
Step 2 — Database Setup
# Example for PostgreSQL
psql -U your_username -d your_database -f sql/create_tables.sql
psql -U your_username -d your_database -f sql/load_data.sql
Step 3 — SQL Queries

Open sql/analysis_queries.sql in pgAdmin, DBeaver, or SSMS

Execute queries to generate insights

Step 4 — Power BI Dashboard

Open dashboard/shopping_dashboard.pbix

Update data source to your database

Refresh and explore the interactive dashboard

📂 Project Structure
shopping-behavior-analysis/
│
├── data/
│   ├── raw/                  # Original dataset
│   └── cleaned/              # Cleaned dataset
│
├── notebooks/
│   ├── 01_EDA.ipynb
│   └── 02_data_cleaning.ipynb
│
├── sql/
│   ├── create_tables.sql
│   ├── load_data.sql
│   └── analysis_queries.sql
│
├── dashboard/
│   └── shopping_dashboard.pbix
│
├── report/
│   └── analysis_report.pdf
│
├── presentation/
│   └── gamma_presentation_link.md
│
├── assets/
│   └── dashboard_preview.png
│
└── README.md
