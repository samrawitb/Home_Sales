## Home Sales Analysis Using PySpark and Spark SQL

This project showcases how PySpark and Spark SQL can be used to analyze a home sales dataset. It highlights data loading, transformation, querying, and performance optimization techniques such as caching and partitioning.

#### Key Features:
- Spark Setup: Configures a Spark environment within a Colab notebook, including Spark installation and session initialization.
- Data Loading: Imports home sales data from an AWS S3 bucket into a Spark DataFrame.
- SQL Queries: Leverages Spark SQL to perform various analyses on the home sales data, such as:
   - Calculating average prices based on different criteria (e.g., number of bedrooms, bathrooms, square footage).
   - Grouping and filtering data according to specific conditions.
   - Measuring query execution times for performance evaluation.
     
- ##### Caching: Demonstrates the use of caching to enhance query performance by keeping data in memory.
- Parquet Partitioning: Explains how to partition Parquet data by a specific column (e.g., date_built) to optimize query speed and storage efficiency.

#### Dependencies:
- PySpark
- Spark (version 3.4.3 or compatible)
