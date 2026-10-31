# Data Loading and Data Storage using Python

## 📌 About This Project

This project focuses on understanding **Data Loading and Data Storage using Python and Pandas**. It covers how to collect data from different sources, load it into Pandas DataFrames, inspect the data, and store it in different file formats and databases.

The main objective of this project is to gain practical knowledge of handling datasets and performing file operations using Python. It includes hands-on examples of reading, writing, converting, and managing data in different formats.

This notebook also demonstrates basic Web Scraping using Python libraries such as Requests and BeautifulSoup to retrieve webpage information.

## 🎯 Objectives

- Understand the process of data loading and data storage.
- Learn how to read data from different file formats.
- Create and save Pandas DataFrames into files.
- Understand different parameters of `pd.read_csv()`.
- Convert data between different file formats.
- Store and retrieve data using SQLite databases.
- Learn basic Web Scraping techniques.
- Understand Pickle and Parquet file formats.

## 📚 Topics Covered

### 1. Introduction to Data Loading and Data Storage
- Understanding data sources.
- Loading data into Pandas DataFrames.
- Data inspection.
- Data storage in different formats.

### 2. Working with CSV Files
- Reading CSV files using `pd.read_csv()`.
- Writing CSV files using `to_csv()`.
- Creating CSV files from DataFrames.
- Understanding separators and delimiters.
- Saving CSV files without index values.

### 3. Reading CSV Files with Different Parameters
- `header` – Handling column headers.
- `index_col` – Setting a column as an index.
- `usecols` – Selecting specific columns.
- `nrows` – Reading a limited number of rows.
- `skiprows` – Skipping specific rows.
- `sep` – Defining different separators.

### 4. Text File Handling (TXT and TSV)
- Creating text files using Python.
- Writing data into text files.
- Reading text files.
- Converting TXT data into CSV format.
- Working with Tab Separated Values (TSV).
- Using `open()` for file operations.

### 5. JSON File Handling
- Converting DataFrames into JSON files.
- Reading JSON files using `pd.read_json()`.
- Writing JSON files using `to_json()`.
- Understanding the records-oriented JSON format.

### 6. Excel File Handling
- Exporting DataFrames into Excel files.
- Reading Excel files using `pd.read_excel()`.
- Writing Excel files using `to_excel()`.

### 7. Pickle File Handling
- Understanding Pickle file format.
- Saving DataFrames using `to_pickle()`.
- Loading Pickle files using `pd.read_pickle()`.
- Storing Python objects in binary format.

### 8. Parquet File Handling
- Introduction to Parquet file format.
- Saving DataFrames using `to_parquet()`.
- Reading Parquet files using `pd.read_parquet()`.
- Understanding columnar data storage.

### 9. Web Scraping
- Introduction to Web Scraping.
- Using the Requests library.
- Fetching webpage content.
- Parsing HTML using BeautifulSoup.
- Extracting webpage title information.

### 10. SQLite Database Operations
- Creating SQLite database connections.
- Creating database tables.
- Inserting records into tables.
- Using SQL INSERT statements.
- Retrieving records using SELECT queries.
- Fetching records using `fetchall()`.
- Committing database changes.
- Closing database connections.

## 🛠️ Technologies and Libraries Used

- **Python:** Main programming language.
- **Pandas:** Data loading, manipulation, and storage.
- **OS:** Working with directories and files.
- **Requests:** Fetching webpage content.
- **BeautifulSoup:** Parsing HTML content.
- **SQLite3:** Database creation and operations.
- **Jupyter Notebook:** Writing and executing Python code.

## 📂 Project Structure

```text
Data-Loading-and-Storage/
│
├── DATA_LOADING_STORAGE.ipynb
│
└── README.md
```

## 💡 Practical Learning Outcomes

After completing this notebook, I gained practical knowledge of:

- Reading and writing data using Pandas.
- Handling CSV, TXT, TSV, JSON, and Excel files.
- Understanding Pickle and Parquet storage formats.
- Converting data between different file formats.
- Performing basic file handling operations.
- Creating and managing SQLite databases.
- Retrieving data from databases using SQL queries.
- Understanding the basics of Web Scraping.

## ▶️ How to Run This Project

1. Clone or download this repository.
2. Open the project in Jupyter Notebook or Google Colab.
3. Install the required Python libraries if they are not already installed.
4. Open `DATA_LOADING_STORAGE.ipynb`.
5. Execute the notebook cells one by one.

### Install Required Libraries

```bash
pip install pandas openpyxl pyarrow requests beautifulsoup4
```

## 👨‍💻 Conclusion

This project provides hands-on experience with different techniques of data loading and data storage using Python. It helps build a strong foundation in handling structured data, working with different file formats, managing databases, and extracting basic information from websites.

This is an important step towards learning Data Science, Data Analysis, and real-world data management.

---

**Project:** Data Loading and Data Storage

**Language:** Python

**Main Library:** Pandas

**Environment:** Jupyter Notebook
This project strengthens my understanding of Python-based data loading and storage techniques and builds a foundation for future learning in Data Science and Data Analysis.
