# ABAP Lottery Statistics

## Overview

Lottery Statistics is an ABAP project developed to import, validate, store, and analyze historical lottery draw results within a SAP environment.

The solution includes a CSV import module, a custom validation function module, and a reporting module that calculates the frequency of lottery numbers and displays the results using SAP ALV reports.

---

## Features

### Data Import

* Import lottery draw results from CSV files.
* Store imported data in a custom SAP database table.
* Simplify the loading of historical lottery information.

### Data Validation

* Validate lottery numbers before processing.
* Check whether numbers are within the valid range (1–60).
* Detect duplicate numbers in a draw.
* Return validation indicators for incorrect entries.

### Data Analysis

* Filter lottery draws by date.
* Analyze selected numbers.
* Calculate the frequency of each number.
* Display results using SAP ALV reports.
* Generate statistics from historical lottery data.

---

## Technologies Used

* ABAP
* SAP ERP
* Open SQL
* Internal Tables
* Function Modules
* SAP ALV (CL_SALV_TABLE)
* CSV File Processing

---

## Project Components

### CSV Import Program

Responsible for importing lottery draw results from CSV files into the SAP database.

### Validation Function Module (Z_BEATEST)

Responsible for validating lottery numbers by:

* Ensuring numbers are between 1 and 60.
* Detecting duplicated numbers.
* Returning validation flags when errors are found.

### Analysis Program

Responsible for:

* Reading lottery draw data.
* Applying filters.
* Counting number occurrences.
* Displaying results in ALV format.

---

## Workflow

1. Import historical draw data from a CSV file.
2. Store the data in a SAP custom table.
3. Validate selected lottery numbers.
4. Process historical records.
5. Count occurrences of each number.
6. Display frequency statistics in an ALV report.

---

## Learning Objectives

This project was developed to practice:

* ABAP Programming
* SAP Database Operations
* CSV Import Processing
* Function Module Development
* Data Validation
* Open SQL Queries
* Internal Tables
* ALV Report Development
* Data Analysis and Aggregation

---

## Author

**Beatriz Chuva**

Computer Science Student | ABAP Developer
