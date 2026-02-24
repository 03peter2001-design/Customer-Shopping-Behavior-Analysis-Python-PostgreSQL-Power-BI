# 👨🏻‍💻 Customer Shopping Behavior Data Analyst Portfolio Project (AI & ML Enhanced)

> This project demonstrates a full, corporate-grade end-to-end data analytics workflow, enhanced with machine learning for customer segmentation and purchase prediction. It mirrors real-world analytics tasks, from raw data ingestion to actionable business insights, interactive dashboards, and reporting.

---

## 📌 Project Overview

The goal of this project is to simulate a professional-grade analytics workflow, showing the ability to transform raw customer transaction data into strategic business intelligence:

✅ **Data Preparation & EDA (Python)**  
- Load, clean, and transform data  
- Explore distributions, missing values, correlations, and trends  

✅ **SQL Analysis (PostgreSQL / MySQL / SQL Server)**  
- Import cleaned data into SQL  
- Run queries to analyze revenue, seasonality, subscription impact, and customer behavior  

✅ **Machine Learning (Python / scikit-learn)**  
- **Customer Segmentation:** Apply KMeans clustering to group customers based on spending and frequency  
- **Purchase Prediction:** Train a model to predict likelihood of subscription or high-value purchase  

✅ **Visualization & Dashboard (Power BI)**  
- Interactive KPIs and charts showing revenue, segmentation, seasonal trends, and ML predictions  
- Filters by age, gender, subscription, category, and season  

✅ **Report & Presentation (Gamma / PowerPoint)**  
- Business insights, key recommendations, and ML interpretations  
- Visual storytelling for stakeholders  

---

## 🔄 End-to-End Workflow

```mermaid
flowchart LR
    A[Raw Data CSV] --> B[Python: EDA & Cleaning]
    B --> C[SQL: Import & Query Analysis]
    C --> D[Machine Learning: Clustering & Prediction]
    D --> E[Power BI: Interactive Dashboard]
    E --> F[Report & Presentation]
🛠️ How to Use This Project

Clone the repository

git clone https://github.com/your-username/customer-shopping-behavior-analysis.git
cd customer-shopping-behavior-analysis

Python Notebooks

01_EDA.ipynb – Load, clean, and explore data

02_Data_Cleaning.ipynb – Data transformations and SQL connection

03_ML_Segmentation_Prediction.ipynb – Customer clustering & purchase prediction

SQL Database

Create database in PostgreSQL/MySQL/MS SQL Server

Load cleaned dataset from Python

Open customer_behavior_sql_queries.sql and run business queries

Power BI Dashboard

Open customer_behavior_dashboard.pbix

Refresh data connection to SQL database

Explore interactive charts, KPIs, segmentation, and ML predictions

Report & Presentation

Summarize findings and recommendations in analysis_report.pdf

Build visual slides using Gamma AI, highlighting business and ML insights

📊 Dashboard & ML Preview

Example of dashboard with ML insights and segmentation

Key Features:

Total Revenue, Average Order Value, Subscription Rate KPIs

Customer Segments from KMeans clustering

Purchase prediction probability for subscription/high-value transactions

Seasonal & category trends, revenue breakdown by age and gender

💡 Key Insights

Top Revenue Category: Clothing contributed 35% of total revenue

Subscription Impact: Subscribers spent 27% more per transaction

Peak Season: Fall drove the highest sales

Customer Segments: 3 distinct groups based on purchase frequency and amount

High-Value Segment Prediction: 42% likely to subscribe or make high-value purchases

Payment Preferences: Credit Card most used; Accessories highest review rating

💼 Business Recommendations

Launch targeted marketing campaigns for high-value customer segments

Promote subscriptions to increase average order value

Adjust inventory and promotions seasonally (Fall peak)

Tailor communications to 25–34 age group

Utilize ML predictions to personalize offers for likely subscribers

🧠 Skills Demonstrated

Data Cleaning & Transformation (Python, Pandas)

Exploratory Data Analysis (EDA, Seaborn, Matplotlib)

SQL Analysis & Business Querying

Machine Learning (KMeans, Classification, Prediction)

KPI Design & Data Storytelling

Interactive Dashboarding (Power BI)

Business Insights Communication

📜 License

MIT License — feel free to fork, star, and use in your portfolio.

👨‍💻 About the Author

Hey, I’m Peter Huang, a Data Analyst.
I specialize in turning raw data into actionable insights using Python, SQL, Power BI, and AI/ML techniques.

🚀 Stay Connected

LinkedIn: Peter Huang

GitHub: Peter Huang

Portfolio: Your Portfolio

💡 Thanks for checking out this project! Star ⭐ this repo if it helped you, and share it with fellow data enthusiasts.
