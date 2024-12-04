
# Joins and Union - SQL Operations

This repository demonstrates SQL operations on two tables: Country and Persons. 

The following tasks are performed:

1. **Inner Join**, **Left Join**, and **Right Join** between the `Country` and `Persons` tables.
2. List all **distinct country names** from both the `Country` and `Persons` tables.
3. List all **country names** from both the `Country` and `Persons` tables, including duplicates.
4. **Round** the ratings of all persons to the nearest integer in the `Persons` table.

## Tables Schema

### 1. Country Table

The `Country` table contains information about various countries. It has the following columns:
- `Id` (INT): Unique identifier for each country.
- `Country_name` (VARCHAR): Name of the country.
- `Population` (INT): Population of the country.
- `Area` (INT): Area of the country (in square kilometers).

### 2. Persons Table

The `Persons` table contains information about persons and their respective countries. It has the following columns:
- `Id` (INT): Unique identifier for each person.
- `Fname` (VARCHAR): First name of the person.
- `Lname` (VARCHAR): Last name of the person.
- `Population` (INT): Population associated with the person's country.
- `Rating` (DECIMAL): Rating assigned to the person.
- `Country_Id` (INT): Foreign key linking to the `Country` table.
- `Country_name` (VARCHAR): Name of the country associated with the person.
