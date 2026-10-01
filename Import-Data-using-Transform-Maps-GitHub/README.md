# Import Data using Transform Maps (Spreadsheet)

## Project Description
This project demonstrates importing employee data from an Excel spreadsheet into ServiceNow using Import Sets and Transform Maps.

## Project Flow
Excel Spreadsheet → Import Set Table → Transform Map → Field Mapping → Coalesce → Employee Test Table → Reports → Dashboard

## Employee Fields
- Employee ID
- Employee Name
- Email
- Department
- Location

## ServiceNow Configuration
- Target table: `u_employee_test`
- Import table: `u_employee_import`
- Transform Map: `Sample Spreadsheet Import`
- Dashboard: `Employee Analytics Dashboards`

## Reports
1. Employees by Department
2. Employees by Location
3. Employee List Report

## Result
Employee records are imported, existing records can be updated using Coalesce, and duplicate records are prevented.
