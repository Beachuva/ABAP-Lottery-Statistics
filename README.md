# Lottery Frequency Analyzer (ABAP)

## Overview

This project is an ABAP application developed to analyze historical lottery draw results stored in a SAP database. The system retrieves lottery data, counts how many times each number has been drawn, and displays the statistics in an ALV report.

## Features

- Retrieve lottery draw results from a SAP custom table.
- Filter data by draw date and selected numbers.
- Calculate the occurrence frequency of each number.
- Display results in an ALV report.
- Generate statistical insights based on historical lottery data.

## Technologies Used

- ABAP
- SAP ERP
- Open SQL
- ALV Grid

## How It Works

1. The application reads lottery draw records from a SAP database table.
2. Users can apply filters such as date ranges or specific numbers.
3. The program processes the data and counts the occurrences of each number.
4. Results are displayed in an ALV report showing the frequency of each lottery number.

## Example Output

| Number | Occurrences |
|--------|-------------|
|   05   |     125     |
|   12   |     118     |
|   23   |     116     |
|   34   |     112     |
|   45   |     109     |

## Project Structure

```text
src/
└── z_projetoloto.abap

README.md
```

## Learning Objectives

This project was developed to practice:

- ABAP programming
- Internal Tables
- Open SQL queries
- Data processing and aggregation
- ALV report generation
- SAP development best practices

## Future Improvements

- Export results to Excel.
- Add graphical statistics.
- Implement advanced filtering options.
- Compare frequencies across different periods.

## Author

Beatriz Chuva

Computer Science Student | ABAP Developer
