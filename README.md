# Awesome ADBC

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome [ADBC](https://arrow.apache.org/adbc/current/index.html) (Arrow Database Connectivity) drivers, tools, and resources.

## Contents

- [Official](#official)
- [Drivers](#drivers)
- [Tools](#tools)
- [Resources](#resources)
  - [Articles](#articles)
  - [Videos](#videos)

## Official

- [Documentation](https://arrow.apache.org/adbc/current/index.html)
- [Repository](https://github.com/apache/arrow-adbc)

## Drivers

- [Amazon Redshift](https://github.com/adbc-drivers/redshift)
- [Arrow Flight SQL](https://github.com/apache/arrow-adbc/tree/main/c/driver/flightsql)
- [BigQuery](https://github.com/adbc-drivers/bigquery)
- [ClickHouse](https://github.com/ClickHouse/adbc_clickhouse)
- [Databricks](https://github.com/adbc-drivers/databricks)
- [DuckDB](https://duckdb.org/docs/current/clients/adbc)
- [Exasol](https://github.com/exasol-labs/exarrow-rs)
- [Microsoft SQL Server](https://github.com/adbc-drivers/mssql)
- [MySQL](https://github.com/adbc-drivers/mysql)
- [PostgreSQL](https://github.com/apache/arrow-adbc/tree/main/c/driver/postgresql)
- [SingleStore](https://github.com/singlestore-labs/singlestore-adbc-connector)
- [Snowflake](https://github.com/adbc-drivers/snowflake)
- [SQLite](https://github.com/apache/arrow-adbc/tree/main/c/driver/sqlite)
- [Trino](https://github.com/adbc-drivers/trino)

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

- [Introducing ADBC: Database Access for Apache Arrow](https://arrow.apache.org/blog/2023/01/05/introducing-arrow-adbc/)
- [How the Apache Arrow Format Accelerates Query Result Transfer](https://arrow.apache.org/blog/2025/01/10/arrow-result-transfer/)
- [Data Wants to Be Free: Fast Data Exchange with Apache Arrow](https://arrow.apache.org/blog/2025/02/28/data-wants-to-be-free/)
- [Fast Streaming Inserts in DuckDB with ADBC](https://arrow.apache.org/blog/2025/03/10/fast-streaming-inserts-in-duckdb-with-adbc/)
- [DuckDB ADBC – Zero-Copy Data Transfer via Arrow Database Connectivity](https://duckdb.org/2023/08/04/adbc)

### Videos

- [Making Moves with Arrow Data: Introducing Arrow Database Connectivity (ADBC)](https://www.youtube.com/watch?v=ot_lOcBCaH4)
- [Where We’re Going, We Don’t Need Rows: Columnar Data Connectivity with Apache Arrow ADBC](https://www.youtube.com/watch?v=TjlmNGNx77E)
