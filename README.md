# oracle-forms-master-detail
Overview

This repository contains Oracle Forms development tasks completed using the HR schema. The project demonstrates key Oracle Forms concepts such as master-detail relationships, LOVs, triggers, sequences, calculated fields, summary columns, calendar integration, and menu customization.

## Technologies Used
Oracle Forms
Oracle Database
PL/SQL
HR Schema

##Features Implemented
###Task 1 - Create Form
Created a new Oracle Form using template.fmb.
###Task 2 - Master Block
Created a master block based on the Departments table.
###Task 3 - Detail Block
Created a detail block based on the Employees table.
###Task 4 - LOV Implementation
Added LOVs for:
Job ID
Department ID
Manager ID
###Task 5 - Total Salary Calculation
Added Total Salary field.
Implemented formula:
Salary * NVL(Commission_Pct, 0)
###Task 6 - Summary Column
Displayed department-wise salary totals.
###Task 7 - Sequence and Trigger
Generated Employee ID and Department ID using sequences and Pre-Insert trigger.
###Task 8 - Calendar Integration
Added calendar functionality for Hire Date.
###Task 9 - Manager LOV
Displayed only employees who are managers.
###Task 10 - Department Creation
Created a new department.
###Task 11 - Department Deletion Validation
Checked deletion restrictions for departments with assigned employees.
###Task 12 - Formatting
Date Format: DD-MM-YYYY
Number Format: 99,99,999.99
###Task 13 - Property Classes
Applied appropriate property classes to form items.
###Task 14 - Menu Integration
Added forms and functions to submenu.
Attached submenu to Batch4/Batch5 menu structure.
