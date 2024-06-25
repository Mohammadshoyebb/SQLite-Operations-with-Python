# SQLite Operations with Python

This repository contains Python scripts that demonstrate basic operations with SQLite databases. It covers database creation, table creation, insertion of records, querying data, updating records, deleting records, and performing aggregate functions.

## Prerequisites

Before running the scripts, ensure you have the following installed:

- Python 3.x (https://www.python.org/)
- SQLite 3 (included in Python standard library)

## Files

### 1. create_connect_db.py

#### Overview
This script demonstrates how to create or connect to an SQLite database using Python.

#### Usage
Run the script to create or connect to an SQLite database named 'sql.db' and retrieve the SQLite version.

### 2. create_table_insert_records.py

#### Overview
This script demonstrates how to create an SQLite table named 'Emp' within the database 'EmpDetails' and insert multiple records into it.

#### Usage
Run the script to create the 'Emp' table if it does not exist, insert sample employee records, and fetch all records from the table.

### 3. select_operations.py

#### Overview
This script demonstrates various SELECT operations on the 'Emp' table including fetching specific columns, applying conditions, ordering results, limiting results, and performing aggregate functions like MIN, MAX, AVG, and SUM.

#### Usage
Run the script to perform different SELECT operations on the 'Emp' table:
- Fetch specific columns 'EmpName' and 'EmpAge'
- Fetch records where 'EmpSalary' is greater than 50000
- Fetch records where 'EmpSalary' is greater than 50000 and 'EmpAge' is less than 30
- Fetch all records ordered by 'EmpSalary' in descending order
- Fetch top 4 records ordered by 'EmpSalary' in descending order
- Update 'EmpSalary' for records where 'EmpDept' is 'DS'
- Delete records where 'EmpDept' is 'IOT'
- Fetch MIN, MAX, AVG, and SUM of 'EmpSalary'
- Fetch 'EmpName' for all records

## Running the Scripts

1. **create_connect_db.py**: 
   - Open a terminal or command prompt.
   - Navigate to the directory containing `create_connect_db.py`.
   - Run `python create_connect_db.py`.

2. **create_table_insert_records.py**: 
   - Open a terminal or command prompt.
   - Navigate to the directory containing `create_table_insert_records.py`.
   - Run `python create_table_insert_records.py`.

3. **select_operations.py**: 
   - Open a terminal or command prompt.
   - Navigate to the directory containing `select_operations.py`.
   - Run `python select_operations.py`.

Ensure you have appropriate permissions to read/write files and execute SQLite operations in your environment.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Authors

- Replace with your name or username.

Feel free to modify and expand upon these scripts to suit your specific requirements and scenarios.

