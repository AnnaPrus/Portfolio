# 🛠️ Data Engineer Portfolio

Hi, I'm Anna. This portfolio is a collection of hands-on data engineering and analytics projects that showcase my practical work across the modern data stack.

The projects here focus on building real workflows end to end: ingesting and transforming data, orchestrating pipelines, working with cloud platforms, modeling datasets for analysis, and delivering insights through dashboards and reporting. They reflect both guided coursework and independent projects developed to deepen my technical skills in data engineering.

### 💡 What you’ll find here:

- End-to-end data pipelines built with Python, SQL, dbt, and Spark
- ETL and ELT workflows with orchestration and cloud integration
- Projects using tools such as GCP, AWS, Airflow, BigQuery, and Docker
- Data modeling, testing, and analytics engineering examples
- Visualization and dashboard-ready datasets
- Continuous learning projects focused on practical implementation

# [Renewable Energy Data Pipeline](https://github.com/AnnaPrus/renewable-energy-pipeline)

- Project Overview: This project builds an end-to-end batch data pipeline for analyzing European electricity demand and renewable energy production. The pipeline ingests raw time-series data, cleans and validates it with Airflow, stores it in Google Cloud Storage and BigQuery, transforms it with dbt, and produces dashboard-ready analytics models.

- Key goals include:
  - Building an orchestrated batch pipeline with Apache Airflow
  - Loading data into a cloud-based data lake and data warehouse
  - Applying dbt transformations to create staging, intermediate, and mart models
  - Optimizing BigQuery tables with partitioning and clustering
  - Analyzing renewable share, demand patterns, and peak load behavior across countries

- Technologies Used:
  - Python and pandas: Data ingestion and cleaning
  - Apache Airflow: Workflow orchestration
  - Google Cloud Storage: Raw data storage
  - BigQuery: Cloud data warehouse
  - dbt: Transformations and testing
  - Terraform: Infrastructure as code
  - Docker: Local environment setup
  - Looker Studio: Dashboarding and visualization

- Final Outcome: An end-to-end cloud-based batch pipeline that produces analytics-ready tables and insights on renewable energy share, electricity demand trends, and supply-demand mismatches in Germany and Austria.


# [Web Scraping - Beautiful Soup](https://github.com/AnnaPrus/web_scrapping/tree/main)

- Project Overview: This project uses web scraping techniques to extract information from a website listing the top 10 largest banks in the world. The scraped data is transformed using Python and pandas, then stored in CSV format and SQLite tables for further querying and analysis.

- Technologies Used:
  - Python: Main programming language
  - Beautiful Soup: Web scraping and HTML parsing
  - Pandas: Data manipulation and transformation
  - SQLite3: Local database storage and querying

- Final Outcome: *[Transformed banks output file](https://github.com/AnnaPrus/web_scrapping/blob/main/banks_transformed.csv)*

# [Data Analysis Using PySpark](https://github.com/AnnaPrus/data_analysis_using_spark)

- Project Overview: This project demonstrates hands-on data analysis using PySpark, the Python API for Apache Spark. It focuses on performing structured transformations, SQL queries, aggregations, and analytical calculations on employee data to simulate real-world data engineering and analytics tasks.

- Key goals include:
  - Loading and structuring CSV data efficiently
  - Defining a custom schema for accurate data types
  - Running SQL queries and DataFrame transformations
  - Solving business-style analytical questions
  - Practicing distributed data processing with Spark

- Technologies Used:
  - PySpark: Distributed data processing and analytics
  - Python 3.x: Core programming language
  - Spark SQL: Querying structured data
  - DataFrame API: Transformations and aggregations
  - Jupyter Notebook/IPython: Interactive development environment
  - findspark: Spark integration in Python

# [M&M Color Count by US State Using Apache Spark](https://github.com/AnnaPrus/count_mnm_with_spark)

- Project Overview: This project processes a CSV dataset of M&M candy counts by color across different US states. Using Apache Spark and PySpark, it reads the data, aggregates counts by color and state, and outputs summarized results.

- Technologies Used:
  - PySpark: Distributed processing with Spark
  - Python: Script development and data handling
  - CSV: Input data format

- Project Structure:

```text
count_mnm_with_spark/
├── mnm_data.csv        # CSV file with M&M counts by color and state
├── count_mnm.py        # Python script that uses Spark to aggregate counts
└── README.md           # Setup instructions and project details
```


<hr style="border: 0.5px solid #ccc;">

[My LinkedIn Profile](https://www.linkedin.com/in/anna-prus-solutions-engineer/)



