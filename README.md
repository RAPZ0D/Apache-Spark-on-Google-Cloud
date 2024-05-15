# Apache-Spark-on-Google-Cloud

[Project 1](#Project-1)

[Project 2](#Project-2)

[Project 3](#Project-3)

[Project 4](#Project-4)

[Project 5](#Project-5)

[Project 6](#Project-6)

## Introduction
Welcome to the Apache Spark on Google Cloud repository! My name is Joel Mendonsa, and I am a data science enthusiast with a background in data integration. During my studies, I had the opportunity to work with Google Cloud Platform (GCP), which inspired me to explore Apache Spark for big data processing.

## Overview
In this repository, I showcase various projects demonstrating the usage of Apache Spark on Google Cloud Platform using PySpark. Apache Spark is a powerful distributed computing framework widely used for processing large-scale data sets, and Google Cloud Platform provides an ideal environment for deploying and running Spark applications.

### Key Points:
- **Data Science Background**: As a student of data science and data integration, I understand the importance of efficient data processing and analysis.
- **Inspiration from GCP**: My experience with Google Cloud Platform during lectures motivated me to explore Apache Spark for big data analytics.
- **Ease of Use**: Leveraging Google Cloud Platform for Spark projects eliminates the need for local installation and setup, making it convenient and accessible.
- **Cloud-Based Approach**: By utilizing Google Cloud Platform services such as Google Dataproc clusters, I demonstrate how to leverage the power of Apache Spark in a cloud environment without the hassle of managing infrastructure.

## Projects
Here's a brief overview of the projects included in this repository:

### Project 1
#### Taxi Trips Analysis
[Project 1: Taxi Trips Analysis](Project%201/Project1.ipynb)
#### Description:
Analyzed taxi trip data from Chicago using Apache Spark on Google Cloud Platform to derive insights.

#### Features:
- **Dataset**: Records of taxi trips in Chicago, including trip details.
- **Spark Jobs**:
  - Loaded dataset from Google Cloud Storage.
  - Conducted EDA.
  - Calculated summary statistics.
  - Converted timestamp columns.
  - Aggregated data for analysis.
- **Data Processing**:
  - Loaded data from GCS.
  - Conducted basic cleaning.
  - Explored data for insights.
  - Aggregated data for analysis.

### Project 2
#### Car Sales Data Analysis
[Project 2: Car Sales Data Analysis](Project%202/Project2.ipynb)

#### Description:
Analyzed car sales data for Canada using Apache Spark on Google Cloud Platform. The dataset contains monthly sales data for different car models.

#### Features:
- **Dataset**: Monthly sales data for various car models in Canada.
- **Data Loading**:
  - Loaded dataset from Google Cloud Storage.
- **Data Processing**:
  - Conducted basic data exploration.
  - Converted timestamp columns.
  - Aggregated data for analysis.
- **Data Export**:
  - Uploaded processed data to Google BigQuery.
  - Stored intermediate results in Google Cloud Storage.

### Project 3
#### BikeShare Data Analysis with Spark SQL
[Project 3: BikeShare Data Analysis](Project%203/Project3.ipynb)

#### Description:
Performed analysis on BikeShare data using Spark SQL. The dataset contains information about bike rentals, including datetime, weather conditions, and rental counts.

#### Features:
- **Dataset**: BikeShare data including datetime, weather conditions, and rental counts.
- **Data Loading**:
  - Loaded dataset from Google Cloud Storage.
- **Data Exploration**:
  - Conducted basic data exploration.
- **Spark SQL Queries**:
  - Utilized Spark SQL for data transformation and analysis.
  - Calculated average temperature for each season.
- **Managed Table Creation**:
  - Saved DataFrame as a managed table in Spark.
- **External Table Creation**:
  - Saved DataFrame as an external table in Spark.
- **Table Management**:
  - Listed, showed, and dropped tables in Spark session.

### Project 4
#### Churn Modelling Analysis and Data Transformation
[Project 4: Churn Modelling Analysis](Project%204/Project4.ipynb)

#### Description:
Performed analysis on a Churn Modelling dataset and transformed it using PySpark. The dataset contains information about customers, including credit score, geography, gender, age, balance, estimated salary, and churn status.

#### Features:
- **Dataset**: Churn Modelling dataset containing customer information.
- **Data Loading**:
  - Loaded dataset from Google Cloud Storage.
- **Data Exploration**:
  - Conducted basic data exploration.
- **Data Transformation**:
  - Filtered data for customers in France between the age of 30 to 65.
- **Table Creation and Saving**:
  - Created a table for the filtered data using Spark SQL.
  - Saved the table to Google Cloud Storage as a Parquet file.
- **Table Verification**:
  - Verified the table creation and data saving process by querying the saved table.

### Project 5
#### Extract, Transform, and Load (ETL) with MySQL, Pandas, and PySpark
[Project 5: ETL with MySQL, Pandas, and PySpark](Project%205/Project5.ipynb)

#### Description:
This project involves extracting data from a MySQL database, transforming it using Pandas and PySpark, and visualizing the transformed data using Matplotlib and Seaborn. The processed data is then stored in a Google Cloud bucket for further use.

#### Features:
- **Database**: MySQL database containing loan data.
- **Data Extraction**:
  - Connected to the MySQL database and fetched loan data.
- **Data Loading**:
  - Loaded the extracted data into a Pandas DataFrame.
- **Data Transformation**:
  - Transformed the data using Pandas and PySpark.
  - Calculated average interest rates per credit policy.
- **Data Visualization**:
  - Visualized the average interest rates per credit policy using Matplotlib and Seaborn.
- **Data Storage**:
  - Stored the transformed data as a CSV file in a Google Cloud bucket.
- **File Verification**:
  - Verified the file upload process by checking the stored data in Google Cloud Storage.

### Project 6
