### Hi there 👋, my name is Nickolas!

#### As a Data Engineer, I specialize in designing and implementing scalable data pipelines to extract, transform, and load data efficiently across various cloud platforms. With a focus on data quality and governance, I build solutions that empower data-driven decision-making. My expertise is transforming raw data into actionable insights through data modeling, ETL, visualization, and exploration.

#### History of effective cloud-native engineering projects, utilization of DevOps tools for version control and dockerization, practice in ETL & data manipulation tools. Recent MSc graduate focusing on big data and ML operations.

Have a look at my end-to-end data engineering projects:

**AWS Serverless Real-Time Weather Data Pipeline**:
In this project, I built two serverless data pipelines using AWS cloud. One to ingest, transform, and visualize real-time Forecast Weather data every week, and another one for Historical Batch data. This project involved leveraging Lambda functions, Kinesis Firehose for streaming data, Glue ETL Workflows for orchestrating the data pipeline by connecting the Glue Crawler, ETL jobs alongside with triggers, Athena for querying transformed data, and Grafana Cloud for interactive data visualization.

**GitHub Repository:** [aws-serverless-project](https://github.com/NickolasB98/aws-serverless-project)  

**Azure Databricks Automated Racing Data Pipeline:**
This project leverages Azure Databricks to analyze Formula 1 race results from the Ergast Developer API (1950-2022). Raw data lands in Azure Data Lake Storage, then undergoes Spark-powered transformations (cleaning, schema application) in Azure Databricks notebooks. Further transformations using Databricks SQL in the Silver Zone prepare the data for analysis. Finally, the processed data resides in the Gold Zone for exploration and reporting. A dynamic trigger based on upcoming race dates ensures the pipeline only runs on race weeks, while Azure Data Factory orchestrates and monitors the entire process.

**GitHub Repository:** [databricks-formula1-pipeline-project](https://github.com/NickolasB98/databricks-formula1-pipeline-project)

**Azure Data Factory Fully Automated CI/CD Covid Reporting Pipeline:**
This project utilizes Azure Data Factory to construct a cloud-based ETL pipeline for ingesting, transforming, and loading COVID-19 data from ECDC and Azure Blob Storage into Azure Data Lake and SQL Database. The pipeline leverages ADF Data Flows for efficient data processing, Databricks for advanced transformations, and Power BI for data visualization. To ensure continuous delivery and improved efficiency, a fully automated CI/CD pipeline is implemented using Azure DevOps and Git.

**GitHub Repository:** [azure-data-factory-cicd-covid-project](https://github.com/NickolasB98/azure-data-factory-cicd-covid-project)

**Azure Tokyo Olympics Data Engineering Pipeline**
This project explores the Tokyo Olympics data using a complete Azure data pipeline. It ingests data from GitHub using Azure Data Factory and stores it in Azure Data Lake Gen2. The data is then transformed in Azure Databricks and analyzed using SQL scripts in Azure Synapse Analytics. The analysis focuses on athletes, coaches, teams, and competition entries, generating insights like top medalist countries and average athletes per discipline.

**GitHub Repository:** [tokyo-olympics-azure-project](https://github.com/NickolasB98/tokyo-olympics-azure-project)

**Azure Synapse NYC Taxi Data Engineering Pipeline**
This project develops a data engineering pipeline on Azure Synapse Analytics to analyze NYC Green taxi trip data (2020-2021). It utilizes various Azure services, including Synapse Data Factory, a Serverless SQL Pool for data ingestion and exploration, Apache Spark Pool for complex data transformations, and AWS QuickSight for data visualization. The project demonstrates the seamless integration of various Azure Synapse services, and the strategic use of different cloud environments to address specific needs.

**GitHub Repository:** [azure-synapse-nyc-taxi-de-project](https://github.com/NickolasB98/azure-synapse-nyc-taxi-de-project)

**Airflow Retail Data Pipeline for Streamlined Analytics and Visualization**: 
This project implements an Airflow-powered data pipeline for retail data. The pipeline incorporated data quality checks using Soda and streamlined data transformation with dbt. Leveraging the Cosmos/Astro extension, dbt models were seamlessly integrated into Airflow workflows. The transformed data was loaded into BigQuery for analysis. Python virtual environments and the Astro SDK enhanced pipeline flexibility and data management. This efficient architecture ensured data accuracy, efficiency, and actionable insights.

**GitHub Repository:** [airflow-bigquery-dbt-retail-project](https://github.com/NickolasB98/airflow-bigquery-dbt-retail-project) 

**Airflow Apple Stocks Data Pipeline Project**:
The Airflow Apple Stocks Data Pipeline project automates the process of fetching, processing, and storing stock market data, specifically for Apple Inc. (AAPL), using Apache Airflow. The pipeline orchestrates various tasks through a Directed Acyclic Graph (DAG) ensuring data integrity and availability. It retrieves stock prices from an API, processes the data using a Docker container with Spark, and stores the results in a PostgreSQL database, with notifications sent via Slack upon completion. This project also includes a Metabase dashboard for visualizing insights derived from the stored data.

**GitHub Repository:** [airflow-apple-stocks-de-project](https://github.com/NickolasB98/airflow-apple-stocks-de-project) 

**AWS and Kafka Real-Time Stock Market Data Pipeline**
The project showcases the integration of Apache Kafka and AWS services to create a robust, real-time data pipeline. This project demonstrates how Kafka ran on an AWS EC2 instance, combined with AWS Glue, Amazon S3, and Athena, can handle large-scale, simulated stock market data with high efficiency in real-time.

**GitHub Repository:** [kafka-aws-stock-market-project](https://github.com/NickolasB98/kafka-aws-stock-market-project)

**End-to-End Analytics: DBT, BigQuery, Looker Studio**: 
I used DBT and BigQuery to construct a customers & orders data transformation pipeline. DBT's SQL-based approach offered a familiar language for data manipulation, streamlining the process. I wrote and tested SQL-based transformations (models) within dbt. These models are executed directly in BigQuery, transforming raw data into a usable format. The transformed data resided in BigQuery. Finally, I connected Looker Studio to the BigQuery instance, enabling interactive data visualization to explore the transformed data through drag-and-drop actions.

**GitHub Repository:** [customers-pipeline-dbt-bigquery-project](https://github.com/NickolasB98/customers-pipeline-dbt-bigquery-project)

**MSc Thesis on Predictive Fairness in Healthcare:** My Master's thesis explored the potential for bias in machine learning models used for patient readmission prediction in healthcare. Through this research, I developed a framework for identifying and mitigating bias in these models, emphasizing the importance of data engineering techniques and explainable AI tools in achieving fair and accurate predictions. The focus of this project is on utilizing xAI techniques and Fair AI Libraries for Machine Learning Bias Management across its life cycle.

**GitHub Repository:** [MSc-TOM-Thesis](https://github.com/NickolasB98/MSc-TOM-Thesis) 

**Skills:** 
Python | ETL | SQL | AWS (Kinesis Firehose, Lambda, Athena, Glue ETL Workflow, Glue Crawler, QuickSight) | GCP (BigQuery, Looker) | Azure (Databricks, ADF, Synapse)| Airflow | Git | Machine Learning | Linux CMD

- 🔭 I’m currently working on hands-on Cloud projects to gain experience in cloud engineering. 
- 🌱 I’m currently learning PySpark and SparkSQL on real-life practice examples. In the meantime, I am getting more experience in Docker, considering it vital to master for my career path. 
- 💬 Open to working on projects that involve building and deploying machine learning pipelines on the cloud. My skills in both cloud and ML can be a valuable asset. 
- 📫 How to reach me: nikolaosdb98@gmail.com


[<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/github.svg' alt='github' height='40'>](https://github.com/NickolasB98)  [<img src='https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/linkedin.svg' alt='linkedin' height='40'>](https://www.linkedin.com/in/nikolaos-biniaris-589517187/)  

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=NickolasB98)](https://github.com/anuraghazra/github-readme-stats)

