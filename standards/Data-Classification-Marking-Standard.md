---
title: "Data Classification Marking Standard"
doc_type: "Standard"
id: "GRS-ISMS-STD-012"
version: "1.0.0"
status: "Draft"
owner: "ISMS Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
related_documents:
  - ../policies/Data-Classification-and-Handling-Policy.md
  - ../standards/Workstation-Baseline.md
references:
  - ISO/IEC 27002:2022 (8.10–8.12)
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Data Classification Marking Standard |
| Document ID | GRS-ISMS-STD-012 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | ISMS Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define consistent methods to apply and display classification labels across documents, emails, files, systems,
and collaboration tools to support correct handling and access control.

## 2. Scope

All information assets subject to the Data Classification & Handling Policy.

## 3. Control Requirements

| Req ID | Requirement | Implementation | Evidence |
|--------|-------------|----------------|----------|
| DCM-01 | Default label | Treat unmarked information as INTERNAL until labeled | AUP; awareness materials |
| DCM-02 | M365 labels | Use Microsoft 365 sensitivity labels for Word/Excel/PowerPoint/Outlook | Label policies; screenshots |
| DCM-03 | Headers/footers | Display label in headers/footers for docs where feasible | Templates; document samples |
| DCM-04 | Email tagging | Include label in email headers/footers or subject per M365 policy | Policy screenshots; samples |
| DCM-05 | File metadata | Store label in file metadata or repository attributes where supported | Metadata examples |
| DCM-06 | Storage tagging | Apply storage tags/ACLs based on label (e.g., buckets/shares) | Storage policy exports |
| DCM-07 | Watermarks | Watermark RESTRICTED artifacts when practicable | Samples |
| DCM-08 | Automation | Auto‑label where possible; require user confirmation for downgrades | DLP/auto‑label configs |
| DCM-09 | Exceptions | Document and approve marking exceptions with compensating controls | Exception records |

## 4. Roles and Responsibilities

The ISMS Manager maintains label definitions and M365 label policies; System Owners implement storage and
repository mappings; users apply labels and verify markings.

## 5. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial marking standard aligned to classification policy. |


