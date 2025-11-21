# Databrick-dbt-customer-analysis
End-to-end data engineering project for retail analytics using dbt on Databricks Lakehouse. Includes modeling of customer, store, sales, date, and return datasets.

This project demonstrates how to build a modern data engineering pipeline using dbt and Databricks.
The pipeline ingests and transforms raw retail datasets — including customers, stores, sales, returns, and date — into clean, validated models ready for analytics.

This project follows industry best practices such as:

Medallion architecture (Bronze → Silver → Gold)

dbt staging, intermediate, and mart layers

Automated testing & documentation

Reusable modular SQL with Jinja

Incremental modeling where applicable
