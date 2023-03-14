# dbt duckdb s3 demo

This project demonstrates how to work with external materializations for dbt-duckdb using a localstack S3 implementation.

## How to run

1) Start up docker compose:

`docker compose up`

2) Attach to container:

`docker exec -it dbt-duckdb-s3-demo-meltano-1 /bin/bash`

3) Run dbt using meltano:

`meltano invoke dbt-duckdb run`
