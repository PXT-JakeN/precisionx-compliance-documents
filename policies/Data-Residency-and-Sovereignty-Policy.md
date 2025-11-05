---
title: "Data Residency & Sovereignty Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-056"
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
  - ./Privacy-and-Data-Protection-Policy.md
  - ./Customer-Data-Handling-and-Confidentiality-Policy.md
  - ../standards/Cloud-Landing-Zone-Standard.md
  - ../standards/Database-Security-Standard.md
references:
  - ISO/IEC 27001:2022 A.5; applicable regional privacy and residency laws
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Data Residency & Sovereignty Policy |
| Document ID | GRS-ISMS-POL-056 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | ISMS Manager |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define requirements to honor contractual and regulatory data residency and sovereignty obligations for
GridSite‑managed information.

## 2. Scope

Customer and internal data stored or processed within GridSite SaaS, cloud infrastructure, and GridColo
environments, including backups and telemetry.

## 3. Policy Statements

GridSite selects cloud regions and providers to meet customer and legal residency requirements. Default hosting
is cloud‑first on approved providers (e.g., Linode, DigitalOcean) with region selection documented per service.
Data flows, storage locations, and cross‑border transfers are inventoried and reviewed; transfers require lawful
mechanisms and encryption in transit and at rest. Backups, logs, and analytics data follow the same residency
constraints; where tooling cannot forward residency‑aware logs, periodic manual exports and review are
performed. Contracts and DPAs specify processing locations and subservice providers. Residency exceptions
require ISMS and Legal approval, customer notification when required, and compensating controls.

## 4. Exceptions

Exceptions must document business justification, lawful transfer mechanism, risk assessment, and expiry.

## 5. Compliance Measurement

Measured via data inventory accuracy, region configuration reviews, backup location attestations, and vendor
report sampling.

## 6. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial data residency & sovereignty policy. |


