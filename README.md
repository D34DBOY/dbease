# Project Overview

This project demonstrates basic data manipulation and database operations using the `Faker` library and a custom `DataBase` class. The project generates random user data, inserts it into a database, and performs various queries.

## Purpose

This project serves several purposes:

1. **Generate Random Data:** Useful for testing applications and databases with simulated data.
2. **Database Management:** Demonstrates how to insert and query data in a simple database setup.
3. **Learning and Experimentation:** Acts as a learning tool for working with random data and basic database operations.

## Requirements

To run this project, you need to have the following Python libraries installed:

- `Faker`
- `random` (part of Python standard library)
- `datetime` (part of Python standard library)
- `dataclasses` (part of Python standard library)
- `sqlite3` (part of Python standard library)
- `configparser` (part of Python standard library)

You can install the `Faker` library using pip:

```bash
pip install faker
```

## Sample Information
In this project, we can create the required tables and update the database by entering information in the database.ini file.
```bash
[user]
id=1
first_name=Mehran
last_name=ahmadi
age=21/12
address=kermanshah
money=1254.35

[admin]
id=0
name=yarnovin
userid=1245555
```

### Usage
1. **Initialize the Database:**
    ```python
    from database.database import DataBase
    db = DataBase()
    ```
