# Week 6 - Spark Architecture and Data Processing

## Objective

Understand Spark architecture and perform efficient data processing using transformations, filtering, schema handling, and optimized file formats.

## Technologies Used

* Python
* PySpark
* Apache Spark
* VS Code

## Topics Covered

### Spark Architecture

* Driver
* Cluster Manager
* Executors
* Client Mode vs Cluster Mode

### Spark Concepts

* Lazy Evaluation
* DAG (Lineage Graph)
* Transformations and Actions
* Predicate Pushdown
* Fault Tolerance

### Data Processing

* Reading CSV Files
* Reading Parquet Files
* Filtering Data
* Selecting Required Columns
* Handling Null Values
* Renaming Columns
* Casting Data Types
* Adding New Columns

## Coding Tasks Completed

### Q3

Read CSV file using:

* header=True
* inferSchema=True

### Q5

Filtered Electronics products and selected:

* product_id
* price

### Q6

* Renamed column old_name to new_name
* Cast price from String to Double

### Q8

Filtered orders where:

* status = 'Completed'
* amount > 1000

### Q10

Created final_price column with 18% tax.

### Q12

Loaded Parquet data, filtered null user_id values, and saved output as CSV.

### Q14

Filtered records where:

* region = 'North'
  OR
* priority = 'High'

## Key Insights

1. Spark improves performance using in-memory processing.
2. Lazy Evaluation optimizes execution plans through DAG.
3. Parquet provides better performance than CSV due to columnar storage.
4. Predicate Pushdown reduces unnecessary data loading.
5. Transformations are executed lazily until an action is triggered.
6. Spark provides fault tolerance using lineage information.
7. Using show() is safer than collect() for large datasets.

## Output

* PySpark Code
* Execution Results
* Screenshots
* Theory Answers

## Author

Bharath Raju
