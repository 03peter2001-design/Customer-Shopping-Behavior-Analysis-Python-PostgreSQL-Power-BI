👨🏻‍💻 Customer Shopping Behavior Analysis
This repository showcases an end-to-end data analytics portfolio project using retail customer shopping data. It follows a realistic analyst workflow: from loading and cleaning data in Python, to running business-focused SQL queries, building a Power BI dashboard, and wrapping everything up in a report and presentation.

The main objective is to transform raw customer shopping data into actionable business insights for a retail company by:

✅ Data Preparation, Modeling & EDA (Python)
Clean, transform, and explore the raw dataset to understand structure, quality, and key patterns.

✅ Data Analysis (SQL)
Load the cleaned data into a SQL database, simulate business transactions, and answer questions on customer segments, loyalty, discounts, and purchase drivers.

✅ Visualization & Insights (Power BI)
Build an interactive dashboard that highlights KPIs, trends, and customer behavior, enabling stakeholders to make data‑driven decisions.

✅ Report & Presentation (Gamma)
Summarize findings and recommendations in a written report and create a presentation deck that clearly communicates insights to non‑technical stakeholders.
​


🧾 Dataset
Transactions: ~3,900 customer purchases

Features: 18 columns covering demographics, products, monetary spend, discounts, reviews, and shipping behavior

Example fields:

Age, Gender, Location, Subscription Status

Item Purchased, Category, Purchase Amount, Season, Size, Color

Discount Applied, Previous Purchases, Review Rating, Shipping Type
​

🛠️ Tools & Technologies
Python – pandas, numpy, matplotlib / seaborn for EDA and cleaning

PostgreSQL / MySQL / SQL Server – SQL queries and business analysis

Power BI – interactive reporting and dashboards

Gamma – slide deck / presentation creation

Git & GitHub – version control and portfolio hosting
​

🚶‍♂️ Project Steps
Clone the repository

bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
Open the main notebook

Open Customer_Shopping_Behavior_Analysis.ipynb, which includes:

Data import

Exploratory data analysis (EDA)

Data cleaning & feature engineering

Loading data into a SQL database
​
​

Load data into SQL

Create a database in PostgreSQL / MySQL / SQL Server

Run the Python notebook to push the cleaned data into SQL

Open customer_behavior_sql_queries.sql and execute queries to answer business questions (revenue by gender, high‑value segments, discount behavior, etc.).
​
​

Build the Power BI Dashboard

Open customer_behavior_dashboard.pbix in Power BI

Point it to your SQL database or exported CSV

Explore interactive visuals for revenue, customer segments, products, and discounts
​

Create Report & Presentation

Write a short project report summarizing the business problem, methods, and key findings

Use Gamma to generate a clean, recruiter‑friendly slide deck from your report
​

(Optional) Follow along with a tutorial

You can pair this project with your own learning notes or external tutorials to show your learning journey.
​

📊 Dashboard
The Power BI dashboard is designed to answer questions such as:

Which customer segments drive the most revenue?

How do discounts and subscriptions affect spending?

Which product categories and items perform the best?

How does behavior vary by age group, gender, or season?
​

Add screenshots of your dashboard in an /images folder and embed them here.

✅ Results & Insights
Examples of insights you can highlight:

High‑value age groups and loyal customer segments

Impact of discounts on revenue vs. margin

Products/categories that should be prioritized in campaigns

Subscription and repeat‑purchase behavior patterns
​
​

Use this section to tell the story of what you found and how it could influence business decisions.

🚀 How to Run Locally
Install dependencies:

bash
pip install -r requirements.txt
Run the Jupyter notebook(s) in order.

Set up your SQL database and update connection details in the notebook / config.

Open the Power BI file and refresh the data source.

Read the report and open the Gamma presentation link (if provided).

📜 License
This project is released under the MIT License.
Feel free to fork, modify, and use it in your own portfolio.
