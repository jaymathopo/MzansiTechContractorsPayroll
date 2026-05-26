Mzansi Tech Contractors Payroll System
Student Information
Name: Johannes Mathopo
Student Number: 20250508
Module: SDT621 – Software Design and Testing C#
Assessment: PM-04 Practical Module
Year: 2026
---
Project Description
This project is a Windows Forms Payroll Application developed in C# for Mzansi Tech Contractors.
The application allows users to:
Capture contractor details
Calculate Gross Pay
Calculate UIF Deduction
Calculate PAYE Deduction
Calculate Membership Fee
Calculate Total Deductions
Calculate Net Pay
The system also includes:
Input validation
Error handling
Unit testing using MSTest
Integration testing
System testing
Retesting and regression testing
---
Business Rules
Hourly Rate
R950.00 per hour
Calculations
Gross Pay
Gross Pay = Hours Worked × Hourly Rate
UIF
UIF = 1% of Gross Pay
PAYE
PAYE = (Gross Pay - (Gross Pay × 0.0575 × Number of Dependents)) × 25%
Membership Fee
Membership Fee = 13% of Gross Pay
Net Pay
Net Pay = Gross Pay − UIF − PAYE − Membership Fee
---
Validation Rules
The application does not allow:
Empty contractor name
Negative hours worked
Negative dependents
Non-numeric values
Dependents greater than 10
---
Technologies Used
C#
Windows Forms
Visual Studio 2022
MSTest Framework
.NET Framework
---
Testing Included
The following tests were completed:
Unit Testing
Integration Testing
System Testing
Retesting
Regression Testing
---
GitHub Repository
https://github.com/jaymathopo/MzansiTechContractorsPayroll
How to Run the Application
Open the solution in Visual Studio 2022
Build the solution
Run the application
Enter contractor details
Click "Calculate Net Pay"
---
Evidence Included
My submission includes:
Application screenshots
MSTest results
Validation testing evidence
Integration testing evidence
System testing evidence
GitHub evidence
Test report
---
Author
Johannes Mathopo
