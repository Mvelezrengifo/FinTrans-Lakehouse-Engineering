FinTrans – End-to-End Lakehouse Engineering in Microsoft Fabric
Overview

End-to-end financial data engineering project implemented in Microsoft Fabric using Lakehouse architecture and Spark.

The project processes 10,000 financial transactions, applies data standardization rules, constructs dimensional models, and generates aggregated analytical tables.

Architecture Flow

CSV → Lakehouse → Spark Transformations → Dimensional Modeling → Aggregated Tables

Data Processing
Cleaning & Standardization

Standardized negative transaction amounts.

Created IsCredit and IsDebit classification flags.

Converted TransactionDate from string to date type.

Validated transaction channels and transaction types.

Dimensional Modeling

Dimensions:

dim_date

dim_account

dim_product

Fact Table:

fact_transaction

The model enables scalable financial analysis and aggregation.

Aggregations Implemented

Monthly total transactions

Monthly total positive transaction amount

Top 5 products by transaction amount

Top 5 accounts by transaction amount

Distribution by transaction type

Distribution by channel

All transformations executed using PySpark and SQL in Microsoft Fabric.

Tools Used

Microsoft Fabric

Lakehouse

PySpark

SQL

Dimensional Modeling

Outcome

Built a structured financial analytics pipeline transforming raw transactional data into analytics-ready tables.