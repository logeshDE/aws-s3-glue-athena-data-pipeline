# aws-s3-glue-athena-data-pipeline
Serverless Data Engineering Pipeline using S3, Glue, and Athena (Free Tier Project)
# 🚀 AWS S3 + Glue + Athena Data Engineering Project

## 📌 Overview

This project demonstrates a **serverless data pipeline** using AWS services:

* Amazon S3 (Storage)
* AWS Glue (ETL)
* Amazon Athena (Querying)

## 🎯 Architecture

Raw Data → S3 → Glue Crawler → Data Catalog → Glue Job → Processed Data → Athena

## 🛠 Tech Stack

* AWS S3
* AWS Glue (Crawler + Jobs)
* AWS Athena
* PySpark

## 📂 Project Structure

```
data/ → sample dataset  
scripts/ → ETL code  
sql/ → Athena queries  
```

## 🔄 Workflow

1. Upload raw data to S3
2. Run Glue Crawler
3. Run Glue Job (ETL)
4. Query using Athena

## 💡 Key Features

* Serverless pipeline
* Data cleaning using PySpark
* SQL-based analytics

## 📊 Sample Query

```sql
SELECT city, COUNT(*) FROM processed_data GROUP BY city;
```

## ⚠️ Cost Optimization

* Used small dataset (<10MB)
* Designed for AWS Free Tier

## 👨‍💻 Author
GitHub: https://github.com/logeshDE
