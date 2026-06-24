🪔 Diwali Sales Data Analysis

An exploratory data analysis (EDA) project on Diwali sales data to uncover customer buying patterns and trends across demographics, states, occupations, and product categories.


📌 Objective

To analyze Diwali sales data and identify which customer segments drive the most revenue — helping businesses make smarter marketing and inventory decisions around the festive season.


📂 Project Structure

Diwali-Sales-Data-Analysis -> Diwali_Sales_Data_Analysis.ipynb -> Diwali Sales Data.csv -> README.md -> requirements.txt

📊 Dataset


File: Diwali Sales Data.csv



Features include: User ID, Customer Name, Gender, Age Group, State, Marital Status, Occupation, Product Category, Product ID, Orders, Amount



🔍 Analysis Covered


Gender — Purchase count and total spending by gender
Age Group — Buying patterns across age groups, segmented by gender
State — Top 10 states by number of orders and total sales amount
Marital Status — Spending behaviour by marital status and gender
Occupation — Which sectors contribute the most buyers and revenue
Product Category — Most popular and highest-grossing product categories
Product ID — Top 10 most ordered products



🧹 Data Cleaning Steps


Dropped irrelevant columns (Status, unnamed1)
Removed null values
Converted Amount column to integer type



📈 Key Findings


Married women aged 26–35 from Uttar Pradesh, Maharashtra, and Karnataka, working in IT, Healthcare, and Aviation, are the most likely buyers — primarily purchasing Food, Clothing, and Electronics.




Females account for more buyers and higher total spending than males
The 26–35 age group dominates purchases across genders
UP, Maharashtra, and Karnataka lead both in order volume and revenue
Married women have the highest purchasing power
Food, Clothing, and Electronics are the top three product categories



🛠️ Tech Stack

Tool             |              Purpose



Python           |             Core language


Pandas           |              Data manipulation


NumPy            |             Numerical operations


Matplotlib       |              Base visualizations


Seaborn          |             Statistical plots


Jupyter Notebook |             Interactive analysis environment


🚀 Getting Started

1. Clone the repository

bashgit clone https://github.com/arnaavattri2004/diwali-sales-analysis.git
cd diwali-sales-analysis

2. Install dependencies

bashpip install -r requirements.txt

3. Launch the notebook

bashjupyter notebook Diwali_Sales_Data_Analysis.ipynb


📋 Requirements

pandas
numpy
matplotlib
seaborn
jupyter

Or install directly:

bashpip install pandas numpy matplotlib seaborn jupyter


🙋 Author

Arnav Attri


GitHub: @arnavattri2004
