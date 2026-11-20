# MAKO Cake and Bakery – Odoo 18 ERP Implementation

**Enterprise Resource Planning | Business Process Modeling | System Implementation**

Academic Group Project · Universitas Esa Unggul · 2026

---

## Project Overview

MAKO Cake and Bakery is an academic group project focused on implementing an integrated Enterprise Resource Planning (ERP) system using Odoo 18.

The project translates previously modeled business processes into an ERP environment by mapping business activities to relevant Odoo modules, configuring system components, simulating operational transactions, and documenting the implementation results.

The implementation covers multiple business functions, including Marketing, CRM, Service, Sales, Inventory, Purchasing, Manufacturing, Quality Control, Accounting, Human Resource Management (HRM), and Expenses.

This repository documents the overall project scope and highlights my individual contribution, particularly in HRM and Expenses implementation, as well as Human Resource business process modeling using BPMN.

## Project Objectives

- Translate business process models into Odoo ERP workflows.
- Map business activities to relevant Odoo modules.
- Configure system components and supporting master data.
- Simulate business transactions across different functional areas.
- Examine integration between business processes and ERP modules.
- Document implementation results and system testing activities.

## Project Scope

The group project covers the following business functions:

| Business Function | Implementation Scope |
|---|---|
| Marketing | Campaign management and email marketing |
| CRM & Service | Customer management, sales pipeline, and service processes |
| Sales & POS | Sales orders, outlet transactions, and payments |
| Inventory & Purchasing | Stock management, procurement, and warehouse operations |
| Manufacturing & Quality Control | Production orders, Bill of Materials (BoM), and quality checks |
| Accounting | Invoices, vendor bills, payments, and financial reports |
| HRM & Expenses | Employee administration, recruitment, attendance, payroll, and reimbursement |

## Team Responsibilities

This project was collaboratively developed by five group members, with responsibilities divided according to business functions.

| Team Member | Assigned Responsibilities |
|---|---|
| Angellica Ivana | Marketing & Accounting |
| Dhany Prasetyo | CRM & Service |
| Silmy Kaffa Anggita | Inventory & Purchasing |
| Deka Syahristiani | Manufacturing & Quality Control |
| Neng Audy Agustin | HRM & Expenses |

## My Individual Contribution

My individual responsibilities focused on the implementation and documentation of Human Resource Management (HRM) and Expenses workflows using Odoo 18.

### 1. Human Resource Management (HRM)

- Created employee master data covering 12 active employees across business departments.
- Configured job positions and their corresponding departments.
- Implemented recruitment records for the Baker position, including applicant selection stages and interview scheduling.
- Created employee contract records.
- Recorded employee attendance and time-off data.
- Documented performance evaluations using Activity and Log Note in the Employees module.
- Prepared a June 2026 payroll batch for five employees.
- Recorded final payroll through Vendor Bill and Vendor Payment.

### 2. Expenses Management

- Reviewed the Expenses dashboard to monitor employee expense records.
- Created employee expense claims for operational activities.
- Configured expense categories and the Employee to Reimburse payment method.
- Processed employee reimbursement transactions until Paid status.
- Reviewed expense summaries and employee expense records through the dashboard.

### 3. Business Process Modeling (BPMN)

- Analyzed Human Resource business processes and operational workflows.
- Modeled HRM workflows using Business Process Model and Notation (BPMN).
- Represented recruitment, employee administration, attendance, time off, performance evaluation, expense claims, and payroll activities.
- Documented relationships between business activities and their corresponding system processes.

## ERP Implementation & Testing

The group project included module-level testing and end-to-end process scenarios to examine how business activities were represented and connected within Odoo.

The group report documented successful module-level testing for HRM and Expenses, including:

- Employee and job position management.
- Recruitment and applicant records.
- Employee contracts, attendance, and time off.
- Payroll batch processing.
- Expense claims and reimbursement.
- Expense dashboard and employee expense summaries.

## Tools & Technologies

| Tool / Technology | Purpose |
|---|---|
| Odoo 18 ERP | ERP implementation and business process simulation |
| PostgreSQL | Database management |
| Draw.io | BPMN process modeling |
| OCA Payroll | Payroll batch processing |
| Google Docs | Collaborative project documentation |

**Odoo Modules Used:**

Employees, Recruitment, Attendances, Time Off, Expenses, Invoicing, CRM, Sales, Point of Sale, Inventory, Purchase, Manufacturing, Quality, Accounting, Project, and Email Marketing.

## Implementation Notes & Limitations

Several implementation adjustments were made to accommodate the available Odoo configuration:

- **Performance Evaluation:** The Appraisals module was unavailable, so performance evaluation activities were documented through Activity and Log Note in the Employees module.
- **Payroll Processing:** The OCA Payroll confirmation workflow could not be completed because the Salary Journal configuration was not fully available. Final payroll was therefore recorded through Vendor Bill and Vendor Payment.
- **Approval Workflows:** Some multi-level approval activities were represented through document statuses and manual processes.
- **System Environment:** The project used simulated business data and was developed for academic implementation purposes, not as a live production ERP deployment.

## Repository Documentation

This repository contains selected documentation and implementation evidence.

- `docs/` – Project overview and implementation documentation.
- `diagrams/` – BPMN diagrams for HRM business processes.
- `screenshots/HRM/` – HRM module configuration and implementation evidence.
- `screenshots/Expenses/` – Expenses and reimbursement implementation evidence.

## Project Information

| Detail | Information |
|---|---|
| Project Name | MAKO Cake and Bakery – Odoo 18 ERP Implementation |
| Project Type | Academic Group Project |
| Course | Integrasi dan Kustomisasi ERP (KJ001) |
| Institution | Universitas Esa Unggul |
| Study Program | Information Systems |
| Year | 2026 |

## Author

**Neng Audy Agustin**

Information Systems Student  
Universitas Esa Unggul

My individual contribution focused on HRM, Expenses, and Business Process Modeling within the group project.
