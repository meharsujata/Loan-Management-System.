# Business Rules
## Loan Management System

| Rule ID | Business Rule |
|---|---|
| BR-01 | Every applicant must have a unique Applicant ID. |
| BR-02 | Every loan record must have a unique Loan ID. |
| BR-03 | Loan amount must be greater than zero. |
| BR-04 | Loan term must be selected from approved loan-term options. |
| BR-05 | Interest rate must be a valid non-negative value. |
| BR-06 | Loan status must follow approved system status values. |
| BR-07 | Only authorized users can create or update loan records. |
| BR-08 | Applicant verification status must be maintained. |
| BR-09 | Payment reminders should be generated 7, 3, and 1 day before the installment due date. |
| BR-10 | An overdue alert should be generated when an installment remains unpaid after its due date. |
| BR-11 | Further payment reminders should stop once the installment is recorded as paid. |
| BR-12 | Management reports should support filtering by loan grade, term, purpose, and status. |

### Important Notes
- Actual loan eligibility criteria must be defined and approved by the business.
- Payment reminder rules require installment schedules and payment records.
- These rules are proposed business requirements, not verified LendingClub policies.