# User Stories and Acceptance Criteria
## Loan Management System

### US-01: Applicant Management
**User Story:** As a loan operations executive, I want to record applicant details so that applicant information is maintained centrally.

**Acceptance Criteria:**
- Users can enter applicant details.
- Each applicant has a unique Applicant ID.
- Required fields must be validated.

### US-02: Loan Record Management
**User Story:** As a loan operations executive, I want to create and update loan records so that loan information remains organized.

**Acceptance Criteria:**
- Each loan has a unique Loan ID.
- Loan amount, purpose, term, and interest rate can be recorded.
- Authorized users can update loan information.

### US-03: Loan Status Tracking
**User Story:** As a management user, I want to view loan statuses so that I can monitor portfolio performance.

**Acceptance Criteria:**
- Loan status is displayed for each record.
- Reports can be filtered by loan status.
- Status summaries are available.

### US-04: Portfolio Dashboard
**User Story:** As a manager, I want a portfolio dashboard so that I can review important loan trends.

**Acceptance Criteria:**
- Dashboard displays total loans.
- Dashboard displays loan status distribution.
- Reports can be filtered by grade, term, and purpose.

### US-05: Payment Reminders
**User Story:** As a borrower, I want to receive reminders before my installment due date so that I can plan payments on time.

**Acceptance Criteria:**
- Reminders are generated 7, 3, and 1 day before the due date.
- A due-date alert is generated.
- Reminders stop after payment is recorded.

### US-06: Overdue Alerts
**User Story:** As a loan operations executive, I want to identify overdue installments so that I can follow up appropriately.

**Acceptance Criteria:**
- The system identifies unpaid installments after their due date.
- An overdue alert is generated.
- Authorized users can view overdue records.

### Note
These are proposed user stories for the conceptual LMS. Payment reminders and overdue alerts require installment schedules and actual payment records, which are not available in the historical dataset.