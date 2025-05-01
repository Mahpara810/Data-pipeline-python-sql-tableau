# Data-pipeline-python-sql-tableau
End-to-end data analytics project using Python, SQL Server, and Tableau for ETL, storage, and visualization.
# End-to-End Data Analytics Project using Python, SQL Server & Tableau
This project demonstrates an end-to-end data analytics workflow — from data extraction and transformation using Python, to storage and querying with SQL Server, and finally data visualization using Tableau. It aims to generate meaningful business insights through automation and reporting.
# Project Structure

```text
ProjectName/
│
├── data/           # Raw or sample datasets
├── python/         # Python scripts for ETL
├── sql/            # SQL scripts (DDL/DML queries)
├── tableau/        # Tableau workbooks (.twb/.twbx files or screenshots)
├── README.md       # Project documentation
└── requirements.txt # Python dependencies
```



# Technologies Used
1. Python (Pandas, SQLAlchemy/pyodbc) – for data extraction, transformation (ETL)

2. SQL Server – for data storage and querying

3. Tableau – for building interactive dashboards

4. Optional: Jupyter Notebook for EDA and testing
# Features
1. Automated ETL using Python

2. Cleaned and normalized data stored in SQL Server

3. Interactive dashboards in Tableau

4. Real-world dataset (customizable)

5. Modular codebase and reusable scripts

# How to Run

## 1. Clone the Repository

```bash
git clone https://github.com/Mahpara810/Data-pipeline-python-sql-tableau
cd Data-pipeline-python-sql-tableau
```
## 2. Set Up the Environment
```bash
pip install -r requirements.txt
```
## 3. Set Up SQL Server
•  Create a new database.
•  Run the SQL scripts in the sql/ folder to set up the necessary tables.
## 4. Load Sample Data
• Ensure the sample data is loaded. If not already included, insert the data manually.

## 5. Run ETL with Python
•  Update the database connection strings in the Python scripts as needed.
•  Execute the ETL script:
```bash
python python/etl_script.py
```
## 6. Open Tableau Dashboard
• Open the .twb or .twbx file from the tableau/ folder using Tableau.

• Connect to your SQL Server database or use the extracted data.

## 7. Explore the Dashboards!
Enjoy exploring the visualized data insights!





# Sample Dashboard
![Capture](https://github.com/user-attachments/assets/792d2dfd-cabe-44b3-920a-2f194f1165a7)




# Use Cases
This template can be adapted for:

1. Sales Performance Analysis

2. Customer Segmentation

3. Financial Reporting

4. Healthcare Data Analysis

5. Marketing Campaign Insights
# Contributions
Contributions are welcome! Please fork the repo, make your changes, and submit a pull request.

# License
This project is licensed under the MIT License.








