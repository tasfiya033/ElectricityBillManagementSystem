# ElectricityBillManagementSystem

## Overview
This SQL script contains the schema and data for an electricity billing system database. It includes tables for managing customers, accounts, billing information, tariffs, administrative data, and more.

## Tables
1. *account*: Stores information about customer accounts, such as account ID, customer ID, account number, and account holder's name.
2. *admin*: Contains data related to administrators, including their IDs, names, and associated customer IDs.
3. *billing*: Manages billing details, including meter numbers, account IDs, customer IDs, monthly units, amount per unit, and total amount.
4. *customer*: Stores customer details such as customer ID, name, address, state, city, and pin code.
5. *elec_board*: Holds data about electricity boards, including board IDs and board names.
6. *invoice*: Manages invoice information, including invoice ID, electricity board ID, account number, tariff ID, reading date, and meter number.
7. *tariff*: Contains tariff details like tariff ID and tariff type.

## Data
The script also includes sample data for each table, providing a realistic representation of the database's functionality. 

## Usage
To use this SQL script, execute it against your preferred SQL database management system. Make sure to adjust any table or column names as needed to fit your specific use case.

## Contributors
- Rujina Akhtar (222-125-227)
- Sumaiya Begum (222-115-216)

## Queries
The script concludes with a sample query that retrieves billing information along with the associated customer names.
