# Functional Requirements Document (FRD)
## Loan Management System

### 1. Purpose
This document defines the proposed functional requirements of the Loan Management System based on the business objectives identified in the BRD.

### 2. Functional Requirements

| ID | Functional Requirement | Description |
|---|---|---|
| FR-01 | Applicant Management | The system should allow authorized users to record and view applicant details. |
| FR-02 | Loan Record Management | Users should be able to create, view, and update loan records. |
| FR-03 | Loan Details | The system should capture loan amount, purpose, interest rate, term, and grade. |
| FR-04 | Verification Tracking | Users should be able to view and update applicant verification status. |
| FR-05 | Loan Status Tracking | The system should display loan statuses such as Fully Paid and Charged Off. |
| FR-06 | Portfolio Reporting | The system should generate reports by loan status, grade, term, and purpose. |
| FR-07 | Dashboard | Management should be able to view key portfolio indicators. |
| FR-08 | Data Filtering | Users should be able to filter loan records and reports using relevant fields. |

### 3. Non-Functional Requirements
- Security: Applicant information should be accessible only to authorized users.
- Performance: Reports should load within an acceptable business-defined time.
- Usability: The interface should be easy for operations and management users.
- Data Accuracy: Loan information should be consistent and validated.
- Availability: The system should meet business-defined availability requirements.

### 4. Assumptions
- Authorized users will maintain applicant and loan information.
- Required loan data will be available for reporting.
- Business stakeholders will define access permissions and reporting targets.

### 5. Limitations
The LendingClub dataset supports historical portfolio analysis but does not contain complete application workflow, document-review history, repayment transactions, or staff assignment records. These functions are proposed system requirements and have not been implemented or tested.