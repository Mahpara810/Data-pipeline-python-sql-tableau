# Data-pipeline-python-sql-tableau
End-to-end data analytics project using Python, SQL Server, and Tableau for ETL, storage, and visualization.
# End-to-End Data Analytics Project using Python, SQL Server & Tableau
This project demonstrates an end-to-end data analytics workflow — from data extraction and transformation using Python, to storage and querying with SQL Server, and finally data visualization using Tableau. It aims to generate meaningful business insights through automation and reporting.
# Project Structure
.
├── data/          # Raw or sample datasets
├── python/        # Python scripts for ETL
├── sql/           # SQL scripts (DDL/DML queries)
├── tableau/       # Tableau workbook (.twb/.twbx files or screenshots)
├── README.md      # Project documentation
└── requirements.txt  # Python dependencies

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

1. Clone the Repository
    cd \
git clone https://github.com/Mahpara810/Data-pipeline-python-sql-tableau
   cd \
cd Data-pipeline-python-sql-tableau
3. Set up Environment
   cd \
pip install -r requirements.txt
5. Set up SQL Server
  1.   Create a database and run the scripts in sql/ to set up tables.

  2.    Load sample data if not already included.
4. Run ETL with Python
   Update connection strings in the Python scripts.
   python python/etl_script.py
5. Open Tableau Dashboard
   1. Open .twb or .twbx file from tableau/ folder.

   2. Connect to SQL Server or use the extracted data.

   3. Explore dashboards!
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








