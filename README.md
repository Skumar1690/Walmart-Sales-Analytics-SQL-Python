# Walmart Sales Analytics – SQL & Python

## Project Overview

This end-to-end data analytics project leverages SQL and Python to analyze Walmart sales data, extract valuable business insights, and solve real-world problems. It involves data cleaning, feature engineering, loading data into databases, and complex SQL querying for actionable insights.

---

## Project Workflow

### 1. Environment Setup

- **Tools**: VS Code, Python, MySQL
- **Objective**: Structured workspace for efficient data handling and analysis

### 2. Kaggle API Configuration

- Download API key from Kaggle profile settings
- Place `kaggle.json` in `.kaggle/` folder and run:
  ```bash
  kaggle datasets download -d najir0123/walmart-10k-sales-datasets
  ```

### 3. Download & Organize Data

- Store datasets in the `data/` folder for accessibility

### 4. Install Libraries & Load Data

```bash
pip install pandas numpy sqlalchemy mysql-connector-python psycopg2
```

- Load data into Pandas DataFrames for initial analysis

### 5. Data Exploration & Cleaning

- Explore: `.info()`, `.describe()`, `.head()`
- Clean: remove duplicates, handle nulls, fix data types, format currency

### 6. Feature Engineering

- Add `Total Amount` column = `unit_price * quantity`

### 7. Load Data into MySQL/PostgreSQL

- Use SQLAlchemy to automate table creation and data loading
- Verify with basic SQL queries

### 8. SQL Analysis for Business Questions

- Analyze revenue trends, best-selling products, peak sales periods, profit margins, and customer behavior using SQL

### 9. Documentation & Publishing

- Publish to GitHub: include README, SQL scripts, Jupyter Notebooks, data or download instructions

---

## Requirements

- **Python 3.8+**
- **SQL Databases**: MySQL
- **Python Libraries**: pandas, numpy, sqlalchemy, mysql-connector-python, psycopg2
- **Kaggle API Key**

## Getting Started

```bash
git clone https://github.com/Skumar1690/Walmart-Sales-Analytics-SQL-Python.git
pip install -r requirements.txt
```

---

## Project Structure

```
|-- data/                     # Raw and processed data
|-- sql_queries/              # SQL scripts
|-- notebooks/                # Jupyter notebooks
|-- README.md                 # Documentation
|-- requirements.txt          # Python libraries
|-- main.py                   # Main Python script
```

---

## Results and Insights

- **Sales Insights**: Top categories, best-performing branches, popular payment modes
- **Profitability**: High-margin products and cities
- **Customer Behavior**: Purchase timing, rating trends

## Future Enhancements

- Dashboard with Tableau or Power BI
- Real-time data pipeline automation
- Integration of more datasets

---

## 📜 License

This project is **free to use** for learning and personal projects. Contact the author for commercial use or collaboration.

---

## Acknowledgments

- **Data Source**: Walmart Sales Dataset from Kaggle
- **Inspiration**: Real-world business problem-solving in sales analytics
