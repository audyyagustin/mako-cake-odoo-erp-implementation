
<h1 align="center">MAKO Cake and Bakery – Odoo 18 ERP Implementation</h1>

<h3 align="center">Enterprise Resource Planning & Business Process Modeling</h3>

<p align="center">
  An academic group project focused on translating business processes into an integrated ERP environment using Odoo 18, covering system configuration, workflow implementation, and cross-functional business operations.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/PROJECT-ACADEMIC%20GROUP%20PROJECT-2563EB?style=for-the-badge" />
  <img src="https://img.shields.io/badge/PLATFORM-ODOO%2018-714B67?style=for-the-badge" />
  <img src="https://img.shields.io/badge/INDIVIDUAL%20FOCUS-HRM%20%26%20EXPENSES-16A34A?style=for-the-badge" />
  <img src="https://img.shields.io/badge/YEAR-2026-64748B?style=for-the-badge" />
</p>

<p align="center">
  <a href="#project-overview">Project Overview</a>
  &nbsp;•&nbsp;
  <a href="#project-scope">Project Scope</a>
  &nbsp;•&nbsp;
  <a href="#team-responsibilities">Team</a>
  &nbsp;•&nbsp;
  <a href="#my-individual-contribution">My Contribution</a>
  &nbsp;•&nbsp;
  <a href="#implementation-highlights">Implementation</a>
  &nbsp;•&nbsp;
  <a href="#tools-and-technologies">Tools</a>
</p>

---

## Project Overview

MAKO Cake and Bakery is an academic group project developed as part of the **Integrasi dan Kustomisasi ERP (KJ001)** course at Universitas Esa Unggul.

The project focuses on implementing an Enterprise Resource Planning (ERP) system using Odoo 18 to support and simulate the company's business operations.

Building on previously developed Business Process Model and Notation (BPMN) diagrams, the project translates business workflows into relevant Odoo modules through process mapping, system configuration, master data preparation, transaction simulation, and implementation testing.

The implementation covers multiple business functions, including Marketing, CRM, Service, Sales, Inventory, Purchasing, Manufacturing, Quality Control, Accounting, Human Resource Management (HRM), and Expenses.

This repository presents the overall group project context and documents my individual contribution, which focuses on **HRM, Expenses, and HRM Business Process Modeling**.

## Project Objectives

- Translate business process models into Odoo ERP workflows.
- Map business activities to appropriate Odoo modules.
- Identify the input data and expected outputs for each business function.
- Configure system components and prepare master data.
- Simulate operational transactions across different modules.
- Examine relationships and integration between business processes.
- Document implementation results and system testing activities.

## Project Scope

The group project covers the following business functions and Odoo modules:

| Business Function | Odoo Modules | Main Activities |
|---|---|---|
| Marketing | Email Marketing, CRM | Campaign management and customer engagement |
| CRM & Service | CRM, Sales | Customer management, lead tracking, and service processes |
| Outlet & Online Orders | Point of Sale (POS), Sales, Website/eCommerce | Sales transactions and online ordering |
| Inventory & Purchasing | Inventory, Purchase | Stock management, procurement, and warehouse operations |
| Manufacturing & Quality Control | Manufacturing, Quality | Production orders, Bill of Materials (BoM), and quality checks |
| Accounting | Accounting, Invoicing | Invoices, vendor bills, payments, and financial reporting |
| HRM & Expenses | Employees, Recruitment, Attendances, Time Off, Payroll, Expenses | Employee administration, recruitment, attendance, payroll, and reimbursement |

## Team Responsibilities

This project was collaboratively developed by five group members, with responsibilities distributed across different business functions.

| Team Member | Assigned Responsibilities |
|---|---|
| Angellica Ivana | Marketing & Accounting |
| Dhany Prasetyo | CRM & Service |
| Silmy Kaffa Anggita | Inventory & Purchasing |
| Deka Syahristiani | Manufacturing & Quality Control |
| **Neng Audy Agustin** | **HRM & Expenses** |

## My Individual Contribution

My individual contribution focused on the implementation and documentation of Human Resource Management (HRM) and Expenses workflows using Odoo 18.

### 1. Human Resource Management (HRM)

- Created employee master data covering 12 active employee records across business departments.
- Configured job positions and their corresponding departments.
- Managed recruitment records for the Baker position, including applicant selection stages and interview scheduling.
- Created employee contract records.
- Recorded employee attendance and time-off data.
- Documented employee performance evaluations using Activity and Log Note in the Employees module.
- Prepared a June 2026 payroll batch for five employees.
- Recorded final payroll through Vendor Bill and Vendor Payment.

### 2. Expenses Management

- Reviewed the Expenses dashboard to monitor employee expense records.
- Created employee expense claims for operational activities.
- Recorded transport reimbursement claims using the Transport Reimbursement category.
- Configured the Employee to Reimburse payment method.
- Processed reimbursement transactions until the payment status reached Paid.
- Reviewed employee expense summaries and dashboard information.

### 3. Business Process Modeling (BPMN)

- Analyzed HR business processes and operational workflows.
- Developed BPMN diagrams to represent HRM activities and process relationships.
- Modeled workflows covering recruitment, employee onboarding, employee administration, attendance, time off, performance evaluation, expense claims, and payroll.
- Documented the relationship between business activities and their corresponding system processes.

## Implementation Highlights

The following results summarize selected implementation activities documented in my individual report.

### HRM Implementation

| Implementation Area | Documented Results |
|---|---|
| Employee Management | 12 active employee records |
| Job Position | Employee positions and department relationships |
| Recruitment | Baker recruitment with accepted and rejected applicant examples |
| Interview | Candidate interview scheduling |
| Employee Contract | Employee contract record |
| Attendance | Attendance records for selected employees |
| Time Off | Approved unpaid leave and sick time off |
| Performance Evaluation | Evaluation documentation through Activity and Log Note |
| Payroll | June 2026 payroll batch for five employees |

**Payroll Simulation Results**

| Description | Amount |
|---|---:|
| Gross Payroll | Rp23,300,000 |
| Unpaid Leave Deductions | Rp431,818 |
| **Final Payroll** | **Rp22,868,182** |

The final payroll was recorded through Vendor Bill and Vendor Payment because the Salary Journal configuration was not fully available for the OCA Payroll confirmation workflow.

### Expenses Implementation

| Implementation Area | Documented Results |
|---|---|
| Expenses Dashboard | Expense summary and monitoring |
| Expense Claim | Employee transport expense claim |
| Expense Category | Transport Reimbursement |
| Payment Method | Employee to Reimburse |
| Reimbursement | Processed until Paid status |
| Expense Monitoring | Employee expense summaries and dashboard |

An example expense claim of **Rp150,000** was recorded for transportation related to purchasing activities.

All figures and transactions presented above represent simulated data used in the academic project, not actual company financial records.

## Business Process Integration

The group project demonstrates how different business functions are connected through Odoo ERP.

The main process relationships include:

- **Marketing → CRM:** Campaign activities support customer engagement and lead generation.
- **CRM → Sales:** Customer opportunities can be followed by sales activities and transactions.
- **Sales/POS → Inventory:** Sales transactions affect product stock availability.
- **Purchase → Inventory:** Supplier purchases and receipts update inventory records.
- **Manufacturing → Inventory & Quality:** Production activities use raw materials, generate finished products, and involve quality checks.
- **HRM & Expenses → Accounting:** Payroll and employee expense transactions are documented as part of financial activities.

These relationships were used as the basis for the group's end-to-end testing scenarios and module integration analysis.

## Testing and Implementation Evaluation

The group report documents module-level testing for the implemented business functions.

The testing covered:

- Marketing and CRM campaign activities.
- Customer management and sales processes.
- POS transactions and online order processes.
- Inventory and purchasing transactions.
- Manufacturing and quality control activities.
- HRM employee administration and payroll.
- Expenses claims and reimbursement.
- Accounting transactions and financial reports.

The group report records successful results for the listed module-level tests.

The project also identifies opportunities for further improvement, particularly in data consistency, workflow automation, warehouse configuration, and end-to-end integration.

## Tools and Technologies

| Tool / Technology | Purpose |
|---|---|
| Odoo 18 ERP | ERP configuration and business process simulation |
| PostgreSQL | Database management |
| OCA Payroll | Payroll batch processing |
| Draw.io | BPMN diagram development |
| Google Docs | Collaborative project documentation |

**Odoo Modules Used**

CRM, Sales, Point of Sale, Website/eCommerce, Inventory, Purchase, Manufacturing, Quality, Accounting, Employees, Recruitment, Attendances, Time Off, and Expenses.

## Implementation Notes & Limitations

Several implementation adjustments were made based on the available Odoo modules and system configuration.

**Performance Evaluation**

The Appraisals module was unavailable in the Odoo environment. Therefore, performance evaluation activities were documented using Activity and Log Note in the Employees module.

**Payroll Processing**

The OCA Payroll confirmation workflow could not be completed because the Salary Journal configuration was not fully available. Final payroll recording and payment were therefore handled through Vendor Bill and Vendor Payment.

**Expenses Management**

The expense claims documented in the individual implementation were internal company expenses and were not reinvoiced to customers.

**Project Environment**

The implementation was conducted as an academic ERP simulation using sample business data. It was not a live production deployment.


## Project Documentation

Explore the project documentation and selected implementation evidence below.

| Documentation | Description |
|---|---|
| [Project Overview](docs/project-overview.md) | Background, objectives, and overall project scope |
| [Individual Contribution](docs/individual-contribution.md) | Detailed documentation of my HRM and Expenses implementation |
| [HRM BPMN Diagram](diagrams/BPMN_HRM.png) | Business process modeling for HRM workflows |
| [HRM Implementation Evidence](screenshots/HRM/) | Selected screenshots of HRM configuration and implementation |
| [Expenses Implementation Evidence](screenshots/Expenses/) | Selected screenshots of expense claims and reimbursement |

## Repository Structure

```text
mako-cake-odoo-erp-implementation/
│
├── README.md
│
├── docs/
│   ├── project-overview.md
│   └── individual-contribution.md
│
├── diagrams/
│   ├── BPMN_HRM.png
│   └── README.md
│
└── screenshots/
    ├── HRM/
    └── Expenses/
```

## Project Information

| Detail | Information |
|---|---|
| Project Name | MAKO Cake and Bakery – Odoo 18 ERP Implementation |
| Project Type | Academic Group Project |
| Course | Integrasi dan Kustomisasi ERP (KJ001) |
| Institution | Universitas Esa Unggul |
| Faculty | Faculty of Computer Science |
| Study Program | Information Systems |
| Year | 2026 |

## Author

**Neng Audy Agustin**

Information Systems Student  
Universitas Esa Unggul

**Individual Focus:** ERP Implementation, Human Resource Management, Expenses Management, and Business Process Modeling.

---

<p align="center">
  <sub>Academic Group Project · Individual Contribution Documentation · 2026</sub>
</p>
