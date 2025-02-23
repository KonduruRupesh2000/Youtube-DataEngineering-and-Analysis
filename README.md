# Youtube DataEngineering and Analysis with AWS

## Overview
End-to-end data engineering project using AWS services and Power BI to analyze YouTube Trending Videos dataset. Built scalable data pipeline and interactive dashboard for multi-region video trend analysis.

## Tech Stack & Architecture
- **AWS Services**: S3, Lambda, Glue, Athena, CloudWatch
- **ETL Pipeline**: JSON to Parquet conversion, automated data crawling and cataloging
- **Visualization**: Power BI dashboard with ODBC connectivity to AWS Data Catalog
- **Dataset**: YouTube Trending Videos data from multiple regions (US, GB, CA)

## Key Implementation Steps
- Created IAM roles and S3 buckets for data storage and access management
- Developed Lambda function for JSON to Parquet conversion with CloudWatch monitoring
- Built Glue ETL jobs for processing regional data and analytics database creation
- Designed comprehensive Power BI dashboard connected to AWS Data Catalog
- Automated pipeline with S3 triggers and monitoring

## Challenges & Solutions
- Resolved CloudWatch logs role permissions for S3 access
- Fixed data type mismatch in Parquet files by implementing proper casting
- Handled non-UTF-8 encoding issues in regional data processing

## Results & Future Work
- Successfully processed data from 3 major regions (CA, US, GB)
- Created interactive dashboard for trend analysis and insights
- Next steps: Automate encoding conversion for remaining regions
