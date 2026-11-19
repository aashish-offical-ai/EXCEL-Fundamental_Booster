# PR-1: Fundamental Booster -- Microsoft Excel

## Project Overview

This repository contains an Excel practice workbook designed to build
and demonstrate fundamental spreadsheet skills using student, sales, and
employee datasets.

**Workbook:** `PR_1_Fundamental_Booster.xlsx`

## Workbook Structure

The workbook contains three worksheets:

### 1. Students Grade

Contains student records and academic performance information.

**Main columns** - Student ID and Name - Math, Science, and English
marks - Enrollment Date - Average Marks - Grade - Math & Science \>80? -
Average \>80?

**Excel concepts demonstrated** - `AVERAGE()` -- calculates average
marks. - `IF()` -- assigns grades and identifies top performers. -
`AND()` -- checks whether both Math and Science marks are above 80. -
`COUNTIFS()` -- counts records meeting a condition. - `AVERAGEIFS()` --
calculates an average for records meeting a condition. - `VLOOKUP()` --
searches for a student's name using a Student ID.

### 2. Sales Data

Contains sales transaction details, including products, regions,
salespeople, amounts, and dates.

**Main columns** - Sales ID - Product - Region - Salesperson - Amount
and Date - Discount % - Discount Amount - Net Sales - Discount Eligible?

**Excel concepts demonstrated** - `IF()` and `OR()` -- calculate
discount rates and eligibility. - Arithmetic formulas -- calculate
discount amount and net sales. - `SUMIFS()` -- totals sales using
multiple conditions. - `SUMIF()` -- totals sales for a selected
product. - `SUBTOTAL()` -- calculates a subtotal for a range. -
`AVERAGE()` -- calculates average sales. - `VLOOKUP()` -- searches
product-related values. - `INDEX()` with `MATCH()` -- retrieves a
salesperson's sales value based on a lookup.

### 3. Employee Data

Contains employee details such as department, salary, and joining date.

**Main columns** - Employee ID and Name - Department - Salary - Joining
Date - Joining Year - Years of Service - Name (UPPER) - Name (lower) -
First Name

**Excel concepts demonstrated** - `YEAR()` -- extracts the joining
year. - `DATEDIF()` -- calculates years of service. - `UPPER()` and
`LOWER()` -- change the case of employee names. - `LEFT()` and `FIND()`
-- extract the first name. - `XLOOKUP()` -- searches for employee
information. - `FLOOR()` -- rounds a numeric value down to a specified
multiple.

## Skills Practiced

-   Organizing and working with tabular data
-   Writing and copying Excel formulas
-   Applying logical conditions
-   Performing conditional calculations
-   Looking up information from datasets
-   Working with dates and text
-   Summarizing student, sales, and employee information

## How to Use

1.  Download or clone this repository.
2.  Open `PR_1_Fundamental_Booster.xlsx` in Microsoft Excel.
3.  Select a worksheet: **Students Grade**, **Sales Data**, or
    **Employee Data**.
4.  Review the existing formulas and sample calculations.
5.  Change or add practice values in the data area and observe the
    formula results.

> **Note:** Some formulas, such as `XLOOKUP()`, require a recent version
> of Microsoft Excel. `DATEDIF()` may not appear in Excel's function
> autocomplete, but it can still be entered directly as a formula.
> Formula results may recalculate when the workbook is opened in Excel.

## Repository Contents

``` text
.
├── PR_1_Fundamental_Booster.xlsx
└── README.md
```

## Purpose

The purpose of this project is to practice fundamental Microsoft Excel
functions through three practical datasets: student grades, sales
transactions, and employee records.
