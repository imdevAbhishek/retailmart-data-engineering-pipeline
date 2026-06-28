# 🛒 RetailMart Data Engineering Pipeline

A beginner-friendly Data Engineering project built using **Python, Pandas, NumPy, SQLite, and SQL**. This project simulates a real-world retail sales pipeline by ingesting raw CSV files, cleaning and transforming the data, loading it into a SQLite database, and generating business insights.

## 📌 Project Overview

RetailMart collects daily sales data from multiple retail stores across India. The raw data contains missing values, duplicate records, and inconsistent data types. This project builds an end-to-end ETL (Extract, Transform, Load) pipeline to clean, process, and analyze the data.

## 🚀 Features

- Load multiple CSV files using Pandas
- Detect and handle missing values
- Remove duplicate records
- Convert columns to appropriate data types
- Merge sales, product, and store datasets
- Calculate total revenue
- Generate business insights using Pandas and NumPy
- Store cleaned data in SQLite
- Execute SQL queries for reporting
- Run the complete ETL pipeline using a single function
- Basic error handling using `try-except`

---

## 📂 Project Structure

```
retailmart-data-engineering-pipeline/
│
├── data/
│   ├── sales_data.csv
│   ├── products.csv
│   └── stores.csv
│
├── database/
│   └── retail_sales.db
│
├── notebook/
│   └── RetailMart.ipynb
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- SQLite3
- SQL
- Google Colab / Jupyter Notebook

---

## 📊 Pipeline Workflow

```
CSV Files
     │
     ▼
Data Ingestion
     │
     ▼
Data Cleaning
     │
     ▼
Data Transformation
     │
     ▼
SQLite Database
     │
     ▼
SQL Queries & Reports
```

---

## 📈 Business Insights Generated

- Total Revenue
- Revenue by City
- Revenue per Store per Day
- Top 3 Best-Selling Products
- Top Selling City
- Total Number of Transactions

---

## ▶️ How to Run

1. Clone this repository

```bash
git clone https://github.com/yourusername/RetailMart.git
```

2. Move into the project folder

```bash
cd RetailMart
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Open the notebook

```bash
jupyter notebook RetailMart.ipynb
```

or open the notebook in **Google Colab**.

5. Run all cells.

---

## 🗃️ Database

The cleaned dataset is stored in a SQLite database named:

```
retail_sales.db
```

Table Name:

```
retail_sales
```

---

## 📌 SQL Queries Included

- Top 3 Best-Selling Products
- Revenue per Store per Day

---

## 📚 Skills Demonstrated

- Data Engineering
- ETL Pipeline
- Data Cleaning
- Data Transformation
- SQL
- SQLite
- Pandas
- NumPy
- Error Handling
- Python Programming

---

## 📄 Assignment

This project was developed as part of a **Data Engineering Technical Assignment** to demonstrate the complete ETL workflow using Python and SQL.

---

## 👨‍💻 Author

**Abhishek Vashishtha**

LinkedIn: https://www.linkedin.com/in/vashishtha-abhishek/

GitHub: https://github.com/imdevAbhishek

---

⭐ If you found this project helpful, consider giving it a star!
