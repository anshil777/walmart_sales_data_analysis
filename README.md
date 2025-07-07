# 🛒 Walmart Sales Data Processing Project

## 📌 Project Overview
This project demonstrates a basic data processing pipeline using Python to clean, transform, and store Walmart sales data into a MySQL database.

---

## 📊 Key Features

- Reads raw CSV sales data (`Walmart.csv`)
- Cleans and preprocesses the data:
  - Removes duplicates and null values
  - Converts price columns to numeric format
  - Computes total sales per transaction
- Saves the cleaned data to a new CSV file
- Establishes a connection with a MySQL database
- Uploads the final cleaned dataset to a table named `walmart` in the MySQL database

---

## 🛠 Technologies Used

- Python 🐍
- pandas 📊
- SQLAlchemy & PyMySQL 🔗
- MySQL 🗃️
- Jupyter Notebook 📒

---

## 📂 Files

- `project.ipynb` - The Jupyter notebook with all data processing and database connection code.
- `Walmart.csv` - Input raw data file.
- `walmart_clean_data.csv` - Output cleaned dataset ready for storage.

---

## 🚀 Getting Started

1. Install required packages:

```bash
pip install pandas sqlalchemy pymysql
