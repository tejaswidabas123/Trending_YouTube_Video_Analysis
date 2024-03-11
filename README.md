# Trending_YouTube_Video_Analysis : YouTube Data Engineering Analysis

## Overview

The YouTube Data Engineering Analysis project focuses on securely managing, streamlining, and analyzing structured and semi-structured YouTube video data. This involves categorizing and analyzing trending metrics to extract valuable insights. The primary objectives include establishing efficient data ingestion mechanisms, developing a robust ETL system, and creating a centralized data lake for storage and scalability.

## Key Features

- Efficient data ingestion mechanisms
- Robust ETL system
- Centralized data lake for storage and scalability
- Utilization of AWS services for seamless integration and scalability
- Interactive querying using AWS Athena
- Visualization of insights using Amazon QuickSight

## Technologies Used

- Python
- AWS (Amazon S3, AWS Glue, AWS Lambda, AWS Athena)
- Apache Spark (PySpark)
- Pandas

## Dataset

The project utilizes a comprehensive dataset from Kaggle, containing statistics on daily popular YouTube videos across various regions. This dataset provides valuable insights into video titles, publication times, views, likes, dislikes, and more.

## Code Files

1. **lambda_function.py**: Contains the AWS Lambda function code for ingesting, transforming, and storing YouTube data using AWS Glue and Amazon S3.
2. **etl_pyspark.py**: PySpark script for data transformation and ETL processes, ensuring data quality and compatibility.

## Usage

To run the Lambda function and PySpark script, ensure that you have the necessary AWS permissions and configurations set up. The Lambda function can be triggered by S3 events, while the PySpark script can be executed in an AWS Glue job or a Spark environment.

## Contributing

Contributions are welcome! Feel free to submit pull requests or open issues for any improvements or suggestions.

## License
