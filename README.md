# Customer Shopping Behavior Analysis 

## Overview

This project analyzes customer shopping behavior using a retail dataset to identify purchasing patterns, customer demographics, and product trends. The goal is to transform raw transactional data into meaningful insights that can support business decision-making.

The project demonstrates a complete data analytics workflow, including data cleaning, exploratory data analysis, SQL-based querying, dashboard visualization, and business reporting.

Key analysis tasks include:

- Data exploration and cleaning using Python

- Analytical queries using SQL

- Interactive dashboard creation using Power BI

- Generating a business report and presentation

## Dataset

The dataset contains customer transaction records including demographic details, purchase behavior, product categories, and customer feedback.

Key Features

- Customer demographics (Age, Gender, Location)

- Product information (Item Purchased, Category, Size, Color)

- Purchase details (Purchase Amount, Season, Shipping Type)

- Customer behavior indicators (Previous Purchases, Frequency of Purchases)

- Marketing indicators (Discount Applied, Promo Code Used)

- Customer satisfaction (Review Rating)

- Subscription status

The dataset is used to analyze customer spending patterns and identify insights for improving business strategies.

## Tools & Technologies

This project uses multiple tools commonly used in data analytics:

- **Python** – Data loading, cleaning, and exploratory data analysis

- **Pandas** / NumPy / Matplotlib / Seaborn – Data manipulation and visualization

- **SQL** (PostgreSQL / MySQL / SQL Server) – Data querying and analysis

- **Power BI** – Interactive dashboard creation

- **Gamma** – Presentation generation

- **GitHub** – Project version control and documentation

## Project Steps
 1. **Data Loading**

The dataset was imported into Python using Pandas for initial inspection and processing.

 2. **Data Cleaning**

Data preprocessing included:

- Handling missing values

- Verifying data types

- Checking for duplicates

- Creating new derived columns such as age groups

 3. **Exploratory Data Analysis (EDA)**

EDA was performed to understand:

- Customer demographics

- Purchase patterns

- Product popularity

- Distribution of ratings and purchase amounts

Visualizations were used to identify trends and relationships within the data.

 4. **SQL Data Analysis**

The cleaned dataset was loaded into a relational database and analyzed using SQL queries.

Example analysis included:

- Revenue by gender

- Spending patterns by age group

- Top rated products

- Subscriber vs non-subscriber spending

- Discount and promo code impact on purchases

 5. **Dashboard Development**

An interactive dashboard was created in Power BI to visualize the results and allow easy exploration of the data.

 6. **Report and Presentation**

A structured project report and presentation were created to summarize the analysis, insights, and business recommendations.

## Power BI Dashboard

The Power BI dashboard provides interactive visualizations to explore customer behavior.

![Dashboard](Power_BI.png)

Dashboard highlights include:

- Revenue distribution by gender

- Spending patterns by age group

- Top products by rating

- Subscription vs non-subscription comparison

- Product category revenue analysis

The dashboard enables stakeholders to quickly identify trends and patterns in customer purchasing behavior.

## Key Results

The analysis produced several insights:

- Customers aged 25–34 contributed the highest revenue

- Subscribers tend to spend more than non-subscribers

- Express shipping customers show higher purchase values

- Certain products rely heavily on discount-based purchases

- Customer purchase frequency strongly correlates with subscription status

These insights can help businesses improve marketing strategies, customer retention, and product offerings.

## How to Run the Project
1. **Clone the Repository**
git clone https://github.com/yourusername/customer-shopping-analysis.git
2. **Install Required Python Libraries**
pip install pandas numpy matplotlib seaborn
3. **Run Python Analysis**

Open the Jupyter Notebook or Python script and run the EDA and data cleaning steps.

4. **Load Data into SQL**

Import the cleaned dataset into PostgreSQL, MySQL, or SQL Server and execute the SQL queries provided in the project.

5. **Open Power BI Dashboard**

Open the Power BI file to explore the interactive visualizations.

6. **Review Report and Presentation**

Check the project report and presentation for a full explanation of the analysis and insights.

## Project Structure
Customer-Shopping-Behavior-Analysis
│
├── dataset
│   └── customer_shopping_behavior.csv
│
├── python
│   └── customer_behavoir.ipynb
│
├── sql
│   └── customer_behavoir.sql
│
├── powerbi
│   └── customer_behavoir_dashboard.pbix
│
├── report
│   └── Customer_Shopping_Behavior_Analysis.pdf
│
├── presentation
│   └── Customer-Shopping-Behavior-Analysis.pptx
│
└── README.md

## Author

**Adnan Ali**  
Data Scientist and Data Analytics Professional with skills in Python, SQL, Power BI and Tableau, focused on extracting insights from customer behavior data.
