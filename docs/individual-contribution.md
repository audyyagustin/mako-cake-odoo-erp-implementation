
# Individual Contribution – HRM & Expenses Implementation

## Overview

As part of the MAKO Cake and Bakery Odoo 18 ERP group project, my individual responsibilities focused on the implementation of Human Resource Management (HRM) and Expenses workflows.

The work involved configuring employee-related data, implementing HR operational processes, managing employee expense claims, and documenting business workflows using Business Process Model and Notation (BPMN).

This document outlines the implementation activities and results covered in my individual project report.

---

## 1. Human Resource Management (HRM)

The HRM implementation focused on managing employee information and supporting the employee lifecycle through Odoo.

### 1.1 Employee Management

- Created 12 active employee records across different business departments.
- Configured employee information, including job positions and department assignments.
- Established employee master data as the foundation for attendance, time off, expenses, and payroll processes.

### 1.2 Job Position Configuration

Configured job positions according to the organizational structure of MAKO Cake and Bakery.

Examples included:
- Baker – Production Department
- Cashier – Sales Outlet
- HR Manager and HR Admin – HR Department
- Accounting & Finance Staff – Accounting & Finance Department

### 1.3 Recruitment Management

Implemented the recruitment process for the Baker position.

Activities included:
- Creating applicant records.
- Managing recruitment stages.
- Recording applicants who passed the selection process.
- Recording applicants who were rejected.
- Tracking candidate progress toward the contract proposal stage.

### 1.4 Interview Scheduling

Scheduled a candidate interview through the Odoo meeting feature.

The interview schedule included:
- Interview position: Baker
- Date: 24 June 2026
- Time: 10:00–11:00
- Location: MAKO Meeting Room
- Participants: HR representative and Production Manager

This implementation connected recruitment activities with the interview scheduling process.

### 1.5 Employee Contract Management

Created employee contract records containing employment information, including:

- Employee name
- Department
- Job position
- Contract start date
- Contract type
- Salary structure
- Wage information

The contract was assigned a Running status for payroll-related processing.

### 1.6 Attendance Management

Used the Odoo Attendances module to record employee check-in and check-out activities.

Attendance records were entered for selected employees to demonstrate the monitoring of employee presence and working hours.

### 1.7 Time Off Management

Implemented employee leave records using the Time Off module.

The implementation covered:
- Unpaid Leave.
- Sick Time Off.
- Leave approval and status monitoring.

Approved leave records were used to demonstrate how employee absence information is maintained in the system and can affect payroll calculations.

### 1.8 Performance Evaluation Documentation

The Appraisals module was unavailable in the Odoo environment.

As an alternative, performance evaluation activities were documented through Activity and Log Note in the Employees module.

An employee performance evaluation was recorded based on feedback from the Production Manager.

### 1.9 Payroll Processing

Prepared a June 2026 payroll batch using OCA Payroll.

The payroll batch covered five employees.

**Payroll Simulation Results**

| Description | Amount |
|---|---:|
| Gross Payroll | Rp23,300,000 |
| Unpaid Leave Deductions | Rp431,818 |
| **Final Payroll** | **Rp22,868,182** |

The unpaid leave deductions were included in the payroll calculation.

### 1.10 Payroll Finalization and Payment

The OCA Payroll confirmation workflow could not be completed because the Salary Journal configuration was not fully available.

To complete the payroll recording process, the following steps were performed:

1. Created a Vendor Bill through the Odoo Invoicing module.
2. Recorded the payroll amount of Rp22,868,182.
3. Used the reference PAYROLL-JUN-2026.
4. Posted the Vendor Bill.
5. Processed the payment through Vendor Payment using the Bank journal.
6. Verified the Paid payment status.

This approach documented the final payroll amount and its payment within the available Odoo configuration.

---

## 2. Expenses Management

The Expenses implementation focused on recording employee operational expenses and managing reimbursement transactions.

### 2.1 Expenses Dashboard

Reviewed the Odoo Expenses dashboard to monitor:

- Recorded employee expenses.
- Expenses requiring validation.
- Expenses awaiting reimbursement.
- Employee expense summaries.

After the recorded reimbursement was processed, the To Validate and To Reimburse values were Rp0.

### 2.2 Employee Expense Claims

Created an employee expense claim for purchasing-related transportation.

**Expense Details**

| Description | Information |
|---|---|
| Employee Role | Purchasing Staff |
| Expense Category | Transport Reimbursement |
| Expense Amount | Rp150,000 |
| Paid By | Employee to Reimburse |
| Purpose | Purchasing-related transportation |

The claim demonstrated how an employee can record expenses paid personally for company operational activities.

### 2.3 Reimbursement Processing

Processed the employee expense claim through the reimbursement workflow.

The process covered:
- Recording the expense claim.
- Reviewing the expense information.
- Processing the reimbursement.
- Confirming the Paid status.

The Paid status indicated that the reimbursement transaction had been completed.

### 2.4 Expense Monitoring

Reviewed expense summaries through the Odoo dashboard.

The dashboard provided information about:
- Employee expense totals.
- Expense transaction summaries.
- Reimbursement status.
- Top Employees expense information.

The Top Reinvoiced Orders section did not display data because the recorded expenses represented internal company costs and were not reinvoiced to customers.

---

## 3. Business Process Modeling (BPMN)

In addition to system implementation, my individual work included analyzing and documenting HRM business processes using Business Process Model and Notation (BPMN).

The process model represented the workflow and responsibilities involved in managing human resources at MAKO Cake and Bakery.

### 3.1 HRM Process Scope

The BPMN model covered:

1. Workforce requirements and recruitment requests.
2. Recruitment review and approval.
3. Job vacancy publication.
4. Candidate screening and interview.
5. Applicant selection and hiring decisions.
6. Employee onboarding and contract creation.
7. Employee administration and training.
8. Attendance and time-off management.
9. Performance evaluation.
10. Employee expense claims and verification.
11. Payroll validation, approval, and payment.

### 3.2 BPMN Diagram

The HRM BPMN diagram illustrates the sequence of business activities, decision points, and stakeholder responsibilities throughout the employee lifecycle.

The diagram is provided separately in the repository under the `diagrams/` directory.

---

## 4. Implementation Summary

The individual implementation produced the following outputs:

| Area | Implementation Output |
|---|---|
| Employee Management | 12 active employee records |
| Job Position | Configured job positions and departments |
| Recruitment | Applicant records and selection stages |
| Interview | Scheduled candidate interview |
| Employee Contract | Employee contract record |
| Attendance | Employee attendance records |
| Time Off | Approved leave records |
| Performance Evaluation | Activity and Log Note documentation |
| Payroll | June 2026 payroll batch and payment record |
| Expenses | Employee expense claim and reimbursement |
| BPMN | HRM business process diagram |

---

## 5. Tools and Technologies

- Odoo 18 ERP
- Employees
- Recruitment
- Attendances
- Time Off
- Expenses
- Invoicing
- OCA Payroll
- Business Process Model and Notation (BPMN)

---

## 6. Individual Contribution Scope

This document represents my individual responsibilities within the MAKO Cake and Bakery group project.

The overall ERP implementation was completed collaboratively by the group, while my assigned scope focused on HRM, Expenses, and the corresponding HRM business process modeling.

The implementation activities documented here reflect the work described in my individual project report. They do not represent the entire group's implementation deliverables.

---

## 7. Source Documentation

Individual Report:

*Implementasi HRM dan Expense pada Odoo di MAKO Cake and Bakery*

Course: Integrasi dan Kustomisasi ERP (KJ001)  
Institution: Universitas Esa Unggul  
Year: 2026

Author: Neng Audy Agustin
