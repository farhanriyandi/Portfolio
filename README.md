# Data Engineer Portfolio
This is a repository of the projects I worked on or currently working on. It is updated regularly.

## Projects:

### ETL World Happiness
Project Overview: This project aims to analyze global happiness data by extracting, transforming, and loading data from various sources to gain insights into factors affecting happiness worldwide.
* Extract: Extract Data from 2 website sources by doing web scraping using Beautiful Soup.
* Transform: During the transformation stage, I adjusted the column names according to the requirements. Since there were two data sources, I merged the datasets using an inner join based on the 'country' column with pandas.
* Load: During the load stage, I loaded the data into PostgreSQL.
* Next, I used Airflow to orchestrate and deploy the processes within the workflow.
* Subsequently, I created data visualizations for the World Happiness project using Looker Studio.
[here link of my ETL World Happines project](https://github.com/farhanriyandi/ETL-World-Happiness)

### ELT-Postgres-DBT-Bigquery-Airflow
This project was created using data available at [here link](https://github.com/farhanriyandi/ELT-Postgres-DBT-Bigquery-Airflow/blob/main/data/init.sql) in a local PostgreSQL database, which includes the tables brands, products, orders, and order_details. The stages are as follows:
* Extract: I extracted data from PostgreSQL.
* Load: The data was then loaded into BigQuery using Airflow.
* Transform: Next, I performed transformations using the DBT tool.
* Orchestration: Finally, I utilized Airflow to orchestrate and distribute the processes within the workflow."
[here link of my ELT Postgres-DBT-Bigquery-Airflow proyek](ELT-Postgres-DBT-Bigquery-Airflow)

### ELT-Snowflake-DBT-Airflow
In this project, I utilized data sources from Snowflake, which I then transformed using DBT before loading it back into Snowflake, and then I i utilized Airflow to orchestrate and distribute the processes within the workflow.
[here link of my ELT Snowflake DBT Airfloww](https://github.com/farhanriyandi/ELT-Snowflake-DBT-Airflow).

## Others
* [Pandas](https://github.com/farhanriyandi/Pandas)
* [Machine Learning](https://github.com/farhanriyandi/Machine-Learning-Portfolio)
* [Bootcamp Data Engineer](https://github.com/orgs/ALTA-DE4-Farhan-Riyandi-22Juni2000/repositories)

[My Linkedin Profile](https://www.linkedin.com/in/farhan-riyandi-67b96b215/)


