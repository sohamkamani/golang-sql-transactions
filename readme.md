# SQL Transactions in Go

This is an example of how to work with SQL transactions in Go. You can read the full blog post [here](https://sohamkamani.com/blog/golang/sql-transactions/)

To run the example:

1. Clone this repo
2. Initialize a new Postgres database
3. Run the [migrations](./migrations.sql) on the database
4. Build and run the [main.go](./main.go) file:
    ```
    go build -o transaction-example
    ./transaction-example
    ```