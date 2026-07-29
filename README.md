# **NEXALEARN SYSTEMS & TECHNOLOGICAL INNOVATION (NXL-S)**
**Business Registration No.:** **RC – 8616801**
#### **Business Automation • Software Development • Digital Transformation • Artificial Intelligence**

### **Cooperative:** **PCMS Limited**

**Document Version:** **1.0**
**Email:** [message@nexasystems.com](mailto:message@nexasystems.com)
**Website:** [www.nexasystems.com](http://www.nexasystems.com)

---

# Product Requirements Document (PRD)

## Payroll-Linked Cooperative Management System

**Prepared by:** NexaLearn Systems & Technological Innovation (NXL-S)

---

# 1. Product Overview

The Payroll-Linked Cooperative Management System is a web-based application designed to automate the financial operations of payroll-linked cooperatives.

The system **does not process payroll or perform salary deductions**. Instead, it imports the official Payroll Deduction Schedule for each payroll cycle, validates the records, updates members' financial accounts, and generates financial reports and account statements.

The application serves as the cooperative's central financial management and accounting platform.

> **Project Assumption:** This proposal is based on an initial cooperative size of **up to 100 active members**. Should the membership increase significantly, pricing may be reviewed to accommodate increased data volume, infrastructure requirements, system optimisation, and support.

---

# 2. Product Goal

To provide a secure, reliable and efficient platform that automates cooperative accounting, member savings, loans, commodity repayments, reconciliation and financial reporting while significantly reducing manual record keeping.

---

# 3. Target Users

* Cooperative Administrator
* Treasurer
* Finance Officer
* Cooperative Member (Self-Service Portal)

---

# 4. Core Features

### Member Management

* Member registration
* Employment information
* Membership status
* Beneficiary management
* Member profile management

### Payroll Processing

* Payroll Deduction Schedule Import (Excel/CSV)
* Data validation
* Preview before posting
* Duplicate detection
* Payroll posting history

### Savings & Credit Management

* Ordinary Savings
* Special Savings
* Festival Savings
* Loan Management
* Commodity Purchase Management
* Interest Management
* Repayment Tracking

### Accounting & Reporting

* Automatic ledger posting
* Member ledger
* Audit trail
* Monthly reconciliation
* Financial reports
* Member account statements
* PDF & Excel export

### Communication

* Email notifications
* Monthly statements
* Loan reminders
* Downloadable PDF statements

---

# 5. Business Philosophy

The application is **record-driven**, not **payroll-driven**.

Its responsibility begins **after** the Payroll Deduction Schedule has been produced.

## Operational Philosophy

```text
                        PAYROLL PROCESS
                               │
                               ▼
              Payroll Deduction Schedule Produced
                               │
                               ▼
               Import into Cooperative System
                               │
                               ▼
                   Validate Imported Records
                               │
                               ▼
                 Update Member Financial Records
                               │
         ┌─────────────────────┼─────────────────────┐
         │                     │                     │
         ▼                     ▼                     ▼
 Ordinary Savings          Loan Records      Commodity Records
         │                     │                     │
         └─────────────────────┼─────────────────────┘
                               │
                               ▼
                Update Accounting & Member Ledger
                               │
                               ▼
               Generate Reports & Member Statements
                               │
                               ▼
                 Email / PDF Distribution
```

---

# 6. Monthly Processing Lifecycle

```text
Payroll Deduction Schedule
           │
           ▼
Import Payroll File
           │
           ▼
Validate Members & Deductions
           │
           ▼
Post Financial Transactions
           │
           ├────────► Ordinary Savings
           ├────────► Special Savings
           ├────────► Festival Savings
           ├────────► Loan Repayments
           ├────────► Commodity Repayments
           ▼
Update Ledgers & Member Accounts
           │
           ▼
Generate Financial Reports
           │
           ▼
Generate Member Statements
           │
           ▼
Email & PDF Distribution
```

---

# 7. Project Deliverables

The project includes:

* Secure Web Application
* Professional Corporate Website
* Administrator Dashboard
* Treasurer Dashboard
* Member Self-Service Portal
* Payroll Import Module
* Savings Management
* Loan Management
* Commodity Management
* Accounting & Ledger
* Reports & Analytics
* PDF Statement Generator
* Email Notification System
* Audit Logs
* User Documentation
* Deployment & Initial Configuration

---

# 8. Pricing

## A. One-Time Implementation Cost

### Solution Architecture & Infrastructure

| Item                                  | Payment Type |     Price |
| ------------------------------------- | ------------ | --------: |
| Solution Architecture & System Design | One-Time     | Quotation |
| Business Email Setup                  | One-Time     |   ₦60,000 |
| File Storage Configuration            | One-Time     |   ₦30,000 |
| Initial Deployment & Configuration    | One-Time     |  Included |

**One-Time Infrastructure Subtotal (excluding Solution Architecture):**

## **₦90,000**

---

### Application Development

The complete Payroll-Linked Cooperative Management System will be developed for a fixed implementation fee.

### **Application Development: ₦400,000**

This includes:

* Professional Corporate Website
* Member Management
* Payroll Processing
* Savings Management
* Loan Management
* Commodity Management
* Accounting & Ledger
* Reports & Analytics
* Notifications
* Member Portal
* Administration & User Management

---

## B. Total One-Time Project Investment

| Item                             |   Amount |
| -------------------------------- | -------: |
| Infrastructure Setup             |  ₦90,000 |
| Complete Application Development | ₦400,000 |

### **Total One-Time Project Cost**

# **₦490,000**

> **Note:** Solution Architecture & System Design is quoted separately where applicable.

---

## C. Annual Infrastructure Renewals

The following services are required to keep the application operational after deployment.

| Service                              | Frequency | Annual Cost |
| ------------------------------------ | --------- | ----------: |
| Domain Registration *(SSL Included)* | Annual    |     ₦25,000 |
| Web Hosting / Cloud Server           | Annual    |    ₦115,200 |
| Email Delivery Service               | Annual    |     ₦60,000 |

### **Annual Infrastructure Renewal Total**

# **₦200,200 per year**

---

## D. Optional Annual Maintenance & Technical Support

| Service                         | Frequency | Annual Cost |
| ------------------------------- | --------- | ----------: |
| Maintenance & Technical Support | Annual    |    ₦180,000 |

*(Equivalent to ₦15,000 per month × 12 months.)*

Maintenance includes:

* Bug fixes
* Security updates
* Performance optimisation
* Technical support
* Minor system improvements
* System monitoring

> Maintenance is optional but highly recommended to ensure the application remains secure, stable and continuously supported.

---

# 9. Cost Assumptions

This proposal assumes:

* Up to **100 active members**
* Single cooperative deployment
* Standard reporting requirements
* Standard payroll import format
* Standard approval workflow

Any additional requirements outside these assumptions may require a revised quotation.

---

# 10. Payment Structure

## Option 1 — Project Implementation Only

### Initial Project Payment

The initial payment consists of the **One-Time Project Cost** plus the **first Annual Infrastructure Renewal**.

| Item                                |   Amount |
| ----------------------------------- | -------: |
| One-Time Project Cost               | ₦490,000 |
| First Annual Infrastructure Renewal | ₦200,200 |

### **Initial Project Payment**

# **₦690,200**

### Subsequent Annual Payment

| Service                              | Annual Cost |
| ------------------------------------ | ----------: |
| Domain Registration *(SSL Included)* |     ₦25,000 |
| Web Hosting / Cloud Server           |    ₦115,200 |
| Email Delivery Service               |     ₦60,000 |

### **Annual Recurring Payment**

# **₦200,200 per year**

---

## Option 2 — Project Implementation + Maintenance Plan

### Initial Project Payment

The initial payment consists of the **One-Time Project Cost**, the **first Annual Infrastructure Renewal**, and the **first Annual Maintenance & Technical Support Fee**.

| Item                                         |   Amount |
| -------------------------------------------- | -------: |
| One-Time Project Cost                        | ₦490,000 |
| First Annual Infrastructure Renewal          | ₦200,200 |
| First Annual Maintenance & Technical Support | ₦180,000 |

### **Initial Project Payment**

# **₦870,200**

### Subsequent Annual Payment

| Service                              | Annual Cost |
| ------------------------------------ | ----------: |
| Domain Registration *(SSL Included)* |     ₦25,000 |
| Web Hosting / Cloud Server           |    ₦115,200 |
| Email Delivery Service               |     ₦60,000 |
| Maintenance & Technical Support      |    ₦180,000 |

### **Annual Recurring Payment**

# **₦380,200 per year**

---

## Payment Summary

| Payment Category                               |            Amount |
| ---------------------------------------------- | ----------------: |
| Initial Project Payment (Without Maintenance)  |      **₦690,200** |
| Annual Recurring Payment (Without Maintenance) | **₦200,200/year** |
| Initial Project Payment (With Maintenance)     |      **₦870,200** |
| Annual Recurring Payment (With Maintenance)    | **₦380,200/year** |

---

# 11. Project Timeline

The estimated implementation period for this project is **six (6) weeks** from the official project commencement date, subject to timely approval of requirements, feedback and provision of required project information.

| Week   | Activities                                                                                        |
| ------ | ------------------------------------------------------------------------------------------------- |
| Week 1 | Project kickoff, requirements confirmation, solution architecture and UI planning                 |
| Week 2 | Database design, member management, authentication and professional corporate website development |
| Week 3 | Payroll processing, savings management and accounting modules                                     |
| Week 4 | Loan management, commodity management and reporting                                               |
| Week 5 | Member portal, notifications, PDF statement generation, testing and quality assurance             |
| Week 6 | User acceptance testing, deployment, user training, documentation and project handover            |

---

# 12. Success Criteria

The solution will be considered successful when it can:

* Accurately import Payroll Deduction Schedules.
* Automatically update member financial records.
* Maintain a complete audit trail.
* Track savings, loans and commodity repayments.
* Generate reliable reports and member statements.
* Reduce manual bookkeeping and reconciliation.
* Provide a secure, transparent and scalable cooperative management platform.

---

# Summary

The Payroll-Linked Cooperative Management System is **not a payroll system**. It is a payroll-linked financial management platform that uses the Payroll Deduction Schedule as its operational input.

By automating reconciliation, savings management, loan tracking, commodity repayments, reporting and member statements, the platform provides cooperatives with an accurate, auditable and scalable solution for managing their financial operations.

The proposed implementation is designed for cooperatives with **up to 100 active members** and includes a **Professional Corporate Website**, the complete management application, deployment and supporting infrastructure, with the flexibility to grow as the cooperative expands.

---

## Prepared By

**NexaLearn Systems & Technological Innovation (NXL-S)**

Business Automation • Software Development • Artificial Intelligence • Digital Transformation

**Business Registration No.:** **[RC/BN: ____________________]**

**Email:** [message@nexasystems.com](mailto:message@nexasystems.com)

**Website:** [www.nexasystems.com](http://www.nexasystems.com)
