# Awesome ADBC

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome [ADBC](https://arrow.apache.org/adbc/current/index.html) (Arrow Database Connectivity) drivers, tools, and resources.

## Contents

- [Official](#official)
- [Drivers](#drivers)
- [Tools](#tools)
- [Resources](#resources)
  - [Articles](#articles)
  - [Examples](#examples)
  - [Videos](#videos)

## Official

- [Documentation](https://arrow.apache.org/adbc/current/index.html) - Official ADBC documentation maintained by the Apache Arrow project.
- [Repository](https://github.com/apache/arrow-adbc) - Official ADBC source code repository hosted under the Apache Software Foundation.

## Drivers

- [Amazon Redshift](https://github.com/adbc-drivers/redshift) - ADBC driver for Amazon Redshift developed by Columnar.
- [Apache DataFusion](https://github.com/adbc-drivers/datafusion) - ADBC driver for Apache DataFusion developed by the ADBC Driver Foundry.
- [Apache Spark](https://github.com/adbc-drivers/spark) - ADBC driver for Apache Spark developed by the ADBC Driver Foundry.
- [Arrow Flight SQL](https://github.com/apache/arrow-adbc/tree/main/c/driver/flightsql) - ADBC driver for Apache Arrow Flight SQL developed under the Apache Software Foundation.
- [BigQuery](https://github.com/adbc-drivers/bigquery) - ADBC driver for BigQuery developed by the ADBC Driver Foundry.
- [ClickHouse](https://github.com/ClickHouse/adbc_clickhouse) - ADBC driver for ClickHouse developed by ClickHouse, Inc.
- [Databricks](https://github.com/adbc-drivers/databricks) - ADBC Driver for Databricks developed by the ADBC Driver Foundry.
- [DuckDB](https://duckdb.org/docs/current/clients/adbc) - ADBC driver for DuckDB developed by the DuckDB Foundation.
- [Exasol](https://github.com/exasol-labs/exarrow-rs) - ADBC driver for Exasol developed by Exasol Labs.
- [Microsoft SQL Server](https://github.com/adbc-drivers/mssql) - ADBC driver for Microsoft SQL Server developed by Columnar.
- [MySQL](https://github.com/adbc-drivers/mysql) - ADBC Driver for MySQL developed by the ADBC Driver Foundry.
- [PostgreSQL](https://github.com/apache/arrow-adbc/tree/main/c/driver/postgresql) - ADBC driver for PostgreSQL developed under the Apache Software Foundation.
- [SingleStore](https://github.com/singlestore-labs/singlestore-adbc-connector) - ADBC driver for SingleStore developed by SingleStore.
- [Snowflake](https://github.com/adbc-drivers/snowflake) - ADBC driver for Snowflake developed under the Apache Software Foundation.
- [SQLite](https://github.com/apache/arrow-adbc/tree/main/c/driver/sqlite) - ADBC driver for SQLite developed under the Apache Software Foundation.
- [Trino](https://github.com/adbc-drivers/trino) - ADBC Driver for Trino developed by the ADBC Driver Foundry.

## Tools

- [databow](https://github.com/columnar-tech/databow) - Command-line tool for querying databases via ADBC.
- [dbc](https://docs.columnar.tech/dbc/) - Command-line tool for installing and managing ADBC drivers.
- [dbt Fusion engine](https://docs.getdbt.com/docs/fusion) - The next-generation engine for dbt.
- [dlt](https://dlthub.com/docs/intro) - Open source Python library that makes data loading easy.
- [Harlequin](https://harlequin.sh/) - SQL IDE for your teminal.
- [Power BI](https://learn.microsoft.com/en-us/power-bi/) - Microsoft's business analytics platform.
- [Polars](https://docs.pola.rs/) - Blazingly fast DataFrame library for manipulating structured data.
- [Sling](https://docs.slingdata.io/) - CLI tool that extracts data from a source and loads it in a target.

## Resources

### Articles

- [Introducing ADBC: Database Access for Apache Arrow](https://arrow.apache.org/blog/2023/01/05/introducing-arrow-adbc/) - Apache Arrow Blog post by the Apache Arrow PMC.
- [How the Apache Arrow Format Accelerates Query Result Transfer](https://arrow.apache.org/blog/2025/01/10/arrow-result-transfer/) - Apache Arrow Blog post by Ian Cook, David Li, and Matt Topol.
- [Data Wants to Be Free: Fast Data Exchange with Apache Arrow](https://arrow.apache.org/blog/2025/02/28/data-wants-to-be-free/) - Apache Arrow Blog post by Ian Cook, David Li, and Matt Topol.
- [Fast Streaming Inserts in DuckDB with ADBC](https://arrow.apache.org/blog/2025/03/10/fast-streaming-inserts-in-duckdb-with-adbc/) - Apache Arrow Blog post by Loïc Alleyne.
- [DuckDB ADBC – Zero-Copy Data Transfer via Arrow Database Connectivity](https://duckdb.org/2023/08/04/adbc) - DuckDB Engineering Blog post by Pedro Holanda.

### Examples

- [ADBC Quickstarts](https://github.com/columnar-tech/adbc-quickstarts) - Simple examples showing how to use ADBC with various databases and query engines.
- [Columnar Cookbook](https://cookbook.columnar.tech/) - Recipes for database connectivity and data interchange with Arrow and ADBC.

### Videos

- [Making Moves with Arrow Data: Introducing Arrow Database Connectivity (ADBC)](https://www.youtube.com/watch?v=ot_lOcBCaH4) - Data Council talk by Matt Topol.
- [Where We’re Going, We Don’t Need Rows: Columnar Data Connectivity with Apache Arrow ADBC](https://www.youtube.com/watch?v=TjlmNGNx77E) - CMU Database Group seminar by Ian Cook.
- [From ODBC to ADBC: Modernizing the Data Stack for AI and Analytics](https://www.youtube.com/watch?v=j75BIlqzhUk) - The Joe Reis Show episode with Ian Cook.
- [ODBC Takes an Arrow to the Kne](https://archive.fosdem.org/2025/schedule/event/fosdem-2025-4803-odbc-takes-an-arrow-to-the-knee/) - FOSDEM talk by Matt Topol.
