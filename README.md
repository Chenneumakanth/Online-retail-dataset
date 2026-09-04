# 🛍️ Online Retail Dataset – Data Analysis & Visualization

## 📌 Project Overview

This project performs **data analysis and visualization on an Online Retail dataset** using Python. The goal is to clean the data, create useful features, explore sales patterns, perform statistical analysis, and generate business insights.

## 🎯 Objectives

* Import and understand the retail dataset
* Handle missing values and duplicate records
* Clean invalid quantity and price values
* Create new features such as `TotalPrice`, `Month`, `Year`, `Hour`, and `DayType`
* Analyze sales by country, month, product, and customer
* Perform statistical analysis
* Create meaningful data visualizations
* Identify important business insights

## 🛠️ Technologies Used

* **Python**
* **Pandas** – Data manipulation and analysis
* **NumPy** – Numerical operations
* **Matplotlib** – Data visualization
* **Seaborn** – Statistical visualization
* **Jupyter Notebook / Google Colab**

## 🧹 Data Cleaning

The project includes:

* Converting `InvoiceDate` into datetime format
* Removing records with missing `CustomerID`
* Removing duplicate records
* Handling invalid or negative `Quantity` values
* Handling invalid `UnitPrice` values

## 🔧 Feature Engineering

New features were created to support analysis:

* `TotalPrice = Quantity × UnitPrice`
* `Date`
* `Month`
* `Year`
* `Hour`
* `Day`
* `DayName`
* `DayType` – Weekday / Weekend
* `OrderSize` – Small / Medium / Bulk
* `CustomerSegment` – Emerging / Developing / Core Market

## 📊 Data Analysis

The project uses:

* `describe()` and `info()` for dataset exploration
* `value_counts()` and `unique()` for categorical analysis
* `groupby()` for country, month, and product analysis
* Aggregation and sorting to identify top customers and countries
* Pivot tables for customer-country analysis
* Statistical measures including mean, median, mode, standard deviation, variance, and percentiles

## 📈 Data Visualization

The following visualizations were created:

* 📉 Line Chart – Monthly sales
* 📊 Bar Chart – Average monthly revenue
* 📦 Histogram – Total price distribution
* 📦 Box Plot – Order quantity distribution
* 📊 Count Plot – Sales by day of the week
* 🎻 Violin Plot – Spending across day types
* 🔥 Heatmap – Correlation between numerical variables
* 🔵 Pair Plot – Relationships across customer segments

## 💡 Business Insights

The analysis identifies:

* Top-performing countries based on sales
* Best sales month
* Peak sales hour
* Highest-value customers
* Most purchased products

These insights can help understand **customer purchasing behavior, sales trends, product demand, and market performance**.

## 📁 Project Structure

```text
Online-Retail-Analysis/
│
├── Online_retail_dataset_Data_visualization.ipynb
├── README.md
└── Online Retail Dataset
```

## 🚀 How to Run

1. Clone or download this repository.
2. Open the `.ipynb` file using **Jupyter Notebook** or **Google Colab**.
3. Install the required libraries if needed:

```bash
pip install pandas numpy matplotlib seaborn openpyxl
```

4. Run the notebook cells sequentially.

## 👩‍💻 About

This project is part of my **Data Science learning journey**, where I am developing practical skills in **Python, Pandas, data cleaning, exploratory data analysis, statistics, and data visualization**.
