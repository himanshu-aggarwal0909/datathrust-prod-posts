---
title: Data Engineer Code Wall
taxonomy:
    category: tutorials
author: "Himanshu Aggarwal"
description: "Code Notes or tutorials for a data engineer"
post_status: draft
---

 
> Code Tutorials -  Code blocks that are extensively required, while working as a data engineer.

<br/>

---
## Big Data 
---

|  Bringing/Syncing data into your Big data Environment |
|--|
|  |
- Fetching data from OLTP on daily basis into s3/hdfs
- Fetching data from cassandra into s3/hdfs

|  Creating Data Pipelines |
|--|
|  |
- Creating your first ETL data pipeline on AWS.

|    Making Data available for analysis   | 
|--|
|  |
- Basics
- Connecting Tableau with your DataMart [ RDS / Redshift ] via JDBC
- Connecting PowerBI with DataMart [ RDS / Redshift ] via JDBC

<br />

---
## Tools
---

| Azkaban |
|--|
|  |

- Setting up azkaban on your local
- Running selected azkaban jobs

| Spark |
|--|
|  |

- Your first program with spark
- Connecting databases via JDBC in pyspark
    - Connecting postgres.
    - Connecting Mysql
    - Connecting redshift
- Connecting Cassandra
- Loading data from Filesystem (local/HDFS/S3)
- Working with UDFs

| Redshift |
|--|
|  |  |

- Creating a table (with efficient distribution style and sort keys)
- Unload Query (downloading data from redshift table to s3)
- Copying data to Redshift
- Creating UDFs
- Querying Data From S3
    - Redshift Spectrum
    - Creating External Schema
    - Creating External Table

| S3 |
|--|
|  |

- Forecasting your S3 costs in a long term
- Optimising S3 Costs
- Archiving data into Glacier or Glacier Deep Archive

| EMR |
|--|
|  |

- Basics
- Creating Transient EMR clusters on daily basis (via AWS SDK)
