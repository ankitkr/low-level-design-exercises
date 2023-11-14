## Problem Statement: Employee Management System Refactoring Continued

Continuing on the previous employee problem, we have introduced a `CalculateTaxesClient` which computes the total tax paid by the company. Let us refactor and add the following functionalities:

1. Taxes for all employees are calculated as follows:
   - 20% income tax
   - 3% professional tax

2. Taxes for employees are calculated based on their employment type:
   1. For full-time employees
      - 30% income tax
      - 2% professional tax
      - 1% education cess

   2. For part-time employees
      - 20% income tax
      - 3% professional tax
      - 1% educational cess

   3. For interns
      - If annual income < 300000 => no tax 
      - Else => only 15% income tax