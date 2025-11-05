---
title: "Customer Data Handling & Confidentiality Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-055"
version: "1.0.0"
status: "Draft"
owner: "ISMS Manager"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ./Data-Classification-and-Handling-Policy.md
  - ../standards/Data-Classification-Marking-Standard.md
  - ./Privacy-and-Data-Protection-Policy.md
  - ./Supplier-and-Third-Party-Risk-Management-Policy.md
  - ../standards/Data-Loss-Prevention-Standard.md
  - ../standards/Database-Security-Standard.md
references:
  - ISO/IEC 27001:2022 A.5, A.8; SOC 2 (Confidentiality, Security)
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Customer Data Handling & Confidentiality Policy |
| Document ID | GRS-ISMS-POL-055 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | ISMS Manager |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Set mandatory requirements for collecting, accessing, processing, transmitting, storing, and disposing of
customer data to preserve confidentiality, integrity, and availability.

## 2. Scope

All GridSite personnel and subservice organizations handling customer data across SaaS, GridColo, and
corporate operations.

## 3. Policy Statements

Customer data shall be classified and labeled per the Data Classification & Handling Policy; by default, customer
data is RESTRICTED unless documented otherwise. Access is least‑privilege, role‑based, and time‑bound;
production data access by developers is prohibited except under approved, logged break‑glass. Data in transit
and at rest is encrypted; secrets and keys are managed via the central vault. Data minimization applies to logs,
support artifacts, and exports; pseudonymization or masking is used for lower environments. External sharing
requires a valid business need, customer authorization where applicable, and an NDA. BYOD devices may not be
used for INTERNAL or RESTRICTED customer data. DLP and email controls enforce outbound policy. Where
systems cannot forward logs of access/changes, periodic manual exports and review are conducted. Data
disposal follows secure destruction requirements with evidence retained. Incidents involving customer data are
managed per the Incident Response Policy and contractual notification terms.

## 4. Exceptions

Exceptions require ISMS approval with risk treatment and customer notification where contractually required.

## 5. Compliance Measurement

Measured via access reviews, DLP events, encryption coverage, and disposal records.

## 6. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial customer data handling & confidentiality policy. |


