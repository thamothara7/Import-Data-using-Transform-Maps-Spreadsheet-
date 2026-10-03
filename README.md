# Import Data using Transform Maps (Spreadsheet)

**Team ID:** SWTID-2026-7764  
**Project date:** 30 September 2026  
**Team members:** Thamothara N; Silambarsan M

## Project summary

This project documents a repeatable employee spreadsheet import into ServiceNow. A five-column workbook is staged in **Employee Import** (`u_employee_import`), processed by the **Sample Spreadsheet Import** Transform Map, and loaded into **Employee Test** (`u_employee_test`). The target fields are Employee ID, Employee Name, Email, Department, and Location, all configured as String fields. The map uses Employee ID coalesce to match existing records.

The deliverable includes three ServiceNow reports—Employees by Department (Pie/Count), Employees by Location (Bar/Count), and Employee List Report—collected on **Employee Analytics Dashboards**. Dashboard sharing is documented for the intended users, groups, or roles.

The import workflow evidence register includes ServiceNow screenshots from the supplied project walkthrough. The supplied walkthrough records a four-row sample run with two inserts and two updates; repeating the same file produced zero inserts, zero updates, and four ignored rows. The supplied Skill Wallet snapshot shows 50% overall progress and 50% for Milestone 1. Dates and progress for the other milestones, formal UAT signatures, and benchmark timings were not supplied, so the documents identify these as unspecified rather than presenting them as completed evidence.

## Document index

### 1. Ideation

- [Brainstorming and Prioritization](1.%20Ideation%20Phase/Brainstorming%20and%20Prioritization.docx) · [PDF](1.%20Ideation%20Phase/Brainstorming%20and%20Prioritization.pdf)
- [Define Problem Statement](1.%20Ideation%20Phase/Define%20Problem%20Statement.docx) · [PDF](1.%20Ideation%20Phase/Define%20Problem%20Statement.pdf)
- [Empathy Map Canvas](1.%20Ideation%20Phase/Empathy%20Map%20Canvas.docx) · [PDF](1.%20Ideation%20Phase/Empathy%20Map%20Canvas.pdf)

### 2. Requirements and analysis

- [Data Flow Diagrams and User Stories](2.%20Requirement%20Analysis/Data%20Flow%20Diagrams%20and%20User%20Stories.docx) · [PDF](2.%20Requirement%20Analysis/Data%20Flow%20Diagrams%20and%20User%20Stories.pdf)
- [Solution Requirements](2.%20Requirement%20Analysis/Solution%20Requirements.docx) · [PDF](2.%20Requirement%20Analysis/Solution%20Requirements.pdf)
- [Technology Stack and Architecture](2.%20Requirement%20Analysis/Technology%20Stack%20and%20Architecture.docx) · [PDF](2.%20Requirement%20Analysis/Technology%20Stack%20and%20Architecture.pdf)
- [Employee Data Import Journey Map](2.%20Requirement%20Analysis/Employee%20Data%20Import%20Journey%20Map.pdf)

### 3. Project design

- [Problem Solution Fit](3.%20Project%20Design%20Phase/Problem%20Solution%20Fit/Problem%20Solution%20Fit.docx) · [PDF](3.%20Project%20Design%20Phase/Problem%20Solution%20Fit/Problem%20Solution%20Fit.pdf) · [Summary PDF](3.%20Project%20Design%20Phase/Problem%20Solution%20Fit/Problem%20Solution%20Fit%20Summary.pdf)
- [Proposed Solution](3.%20Project%20Design%20Phase/Proposed%20Solution/Proposed%20Solution.docx) · [PDF](3.%20Project%20Design%20Phase/Proposed%20Solution/Proposed%20Solution.pdf)
- [Solution Architecture](3.%20Project%20Design%20Phase/Solution%20Architecture/Solution%20Architecture.docx) · [PDF](3.%20Project%20Design%20Phase/Solution%20Architecture/Solution%20Architecture.pdf)

### 4. Project planning

- [Project Planning and Milestones](4.%20Project%20Planning%20Phase/Project%20Planning%20and%20Milestones.docx) · [PDF](4.%20Project%20Planning%20Phase/Project%20Planning%20and%20Milestones.pdf)
- [Project Planning Logic](4.%20Project%20Planning%20Phase/Project%20Planning%20Logic.docx) · [PDF](4.%20Project%20Planning%20Phase/Project%20Planning%20Logic.pdf)

### 5. Development and validation

- [Data Import Configuration Evidence](5.%20Project%20Development%20Phase/Validation%20and%20Testing/Data%20Import%20Configuration%20Evidence.docx) · [PDF](5.%20Project%20Development%20Phase/Validation%20and%20Testing/Data%20Import%20Configuration%20Evidence.pdf)
- [Data Quality and Coalesce Evidence](5.%20Project%20Development%20Phase/Validation%20and%20Testing/Data%20Quality%20and%20Coalesce%20Evidence.docx) · [PDF](5.%20Project%20Development%20Phase/Validation%20and%20Testing/Data%20Quality%20and%20Coalesce%20Evidence.pdf)
- [Import Workflow Evidence](5.%20Project%20Development%20Phase/Validation%20and%20Testing/Import%20Workflow%20Evidence.docx) · [PDF](5.%20Project%20Development%20Phase/Validation%20and%20Testing/Import%20Workflow%20Evidence.pdf)
- [Reports and Dashboard Validation](5.%20Project%20Development%20Phase/Validation%20and%20Testing/Reports%20and%20Dashboard%20Validation.docx) · [PDF](5.%20Project%20Development%20Phase/Validation%20and%20Testing/Reports%20and%20Dashboard%20Validation.pdf)
- [Reporting Performance Evidence](5.%20Project%20Development%20Phase/Validation%20and%20Testing/Reporting%20Performance%20Evidence.docx) · [PDF](5.%20Project%20Development%20Phase/Validation%20and%20Testing/Reporting%20Performance%20Evidence.pdf)
- [Functional and Performance Test Plan](5.%20Project%20Development%20Phase/Validation%20and%20Testing/Functional%20and%20Performance%20Test%20Plan.docx) · [PDF](5.%20Project%20Development%20Phase/Validation%20and%20Testing/Functional%20and%20Performance%20Test%20Plan.pdf)
- [User Acceptance Testing](5.%20Project%20Development%20Phase/User%20Acceptance%20Testing/User%20Acceptance%20Testing.docx) · [Report PDF](5.%20Project%20Development%20Phase/User%20Acceptance%20Testing/User%20Acceptance%20Testing%20Report.pdf)

### 6. Project documentation

- [Functional Specification Document](6.%20Project%20Documentation/Functional%20Specification%20Document.docx) · [PDF](6.%20Project%20Documentation/Functional%20Specification%20Document.pdf)
- [Final Project Report](6.%20Project%20Documentation/Final%20Project%20Report.pdf)
# Import-Data-using-Transform-Maps-Spreadsheet-
