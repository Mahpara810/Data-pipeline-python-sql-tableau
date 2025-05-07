# Data-pipeline-python-sql-tableau
End-to-end data analytics project using Python, SQL Server, and Tableau for ETL, storage, and visualization.
# End-to-End Data Analytics Project using Python, SQL Server & Tableau
This project demonstrates an end-to-end data analytics workflow — from data extraction and transformation using Python, to storage and querying with SQL Server, and finally data visualization using Tableau. It aims to generate meaningful business insights through automation and reporting.
# 📁 Project Structure

```text
Data-pipeline-python-sql-tableau/
│
├── data/               # Raw or sample datasets
├── python/             # Python scripts for ETL
├── sql/                # SQL scripts (DDL/DML queries)
├── tableau/            # Tableau workbooks (.twb/.twbx files or screenshots)
├── README.md           # Project documentation
└── requirements.txt    # Python dependencies
```



# 💻 Technologies Used
• Python (Pandas, SQLAlchemy/pyodbc) – for data extraction, transformation (ETL)

• SQL Server – for data storage and querying

• Tableau – for building interactive dashboards

• Jupyter Notebook – for EDA and testing
# ✨ Features
• Automated ETL using Python

• Cleaned and normalized data stored in SQL Server

• Interactive dashboards in Tableau

• Real-world dataset (customizable)

• Modular codebase and reusable scripts

# 🚀  How to Run

## 1. Clone the Repository

```bash
git clone https://github.com/Mahpara810/Data-pipeline-python-sql-tableau
cd Data-pipeline-python-sql-tableau
```
## 2. Set Up the Environment
```bash
pip install -r requirements.txt
```
## 3. Data Source

The dataset used in this project is publicly available on Kaggle:  

[Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
## 4 Run the ETL and Data Modeling Notebook

• Open the Jupyter Notebook:  
  `notebooks/Telecom-customer-churn.ipynb`

• This notebook performs:
  - Data loading and cleaning  
  - Transformation into a star schema (fact and dimension tables)  
  - Uploading the transformed data into the existing tables in the SQL Server database.

• Ensure your SQL Server connection details (host, database, username, password) are correctly configured in the notebook.

• After connecting, verify that data of the fact and dimension tables have been successfully loaded into SQL Server.
## 5. Set Up SQL Server
•  Create a new database.

• Run the SQL scripts in the sql/ folder to create the required tables.

• Make a connection to SQL Server from the Jupyter notebook using pyodbc or sqlalchemy.

• Push the cleaned and transformed data from the notebook into the SQL Server tables using pandas.to_sql() or SQL queries.

## 6. Open Tableau Dashboard
• Open the .twb or .twbx file from the tableau/ folder using Tableau.

• Connect to your SQL Server database, or use the extracted data embedded in the workbook.

## 7. Explore the Dashboards!
• Explore and analyze the visualized data insights to uncover trends, patterns, and key metrics.



# 📊 Dashboard
![Capture](https://github.com/user-attachments/assets/792d2dfd-cabe-44b3-920a-2f194f1165a7)




# ✅ Use Cases
This template can be adapted for:

• Sales Performance Analysis

• Customer Segmentation

• Financial Reporting

• Healthcare Data Analysis

• Marketing Campaign Insights
 #  📚 Resources and References
## 1. Dataset Source:
[Telco Customer Churn Dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
This dataset, provided by IBM Sample Data Sets, includes information about a telecom company's customers, such as services signed up for, customer account information, and whether or not the customer churned. It's commonly used for customer retention and churn prediction modeling.

## 2. Official Library Documentation:

• Pandas Documentation

• NumPy Documentation

• Matplotlib Documentation

• Seaborn Documentation

• Scikit-learn Documentation

## 📘 Additional Learning Resources (if applicable):

• IBM Developer – Predict customer churn with SciKit-Learn

• Medium Article – Customer Churn Prediction with Telco Dataset
# 🌟 Acknowledgments
• Thanks to IBM Sample Data Sets for providing the Telco Customer Churn dataset.

• Special thanks to Kaggle for hosting and making the dataset easily accessible to the data science community.

• Gratitude to the open-source community behind tools like Pandas, NumPy, Matplotlib and Seaborn.

• Appreciation to the authors of various tutorials and blog posts that helped guide the data exploration and model building process.
# 🤝Contributions
Contributions are welcome! Please fork the repo, make your changes, and submit a pull request.

# 📝 License
This project is licensed under the [MIT License](LICENSE).









