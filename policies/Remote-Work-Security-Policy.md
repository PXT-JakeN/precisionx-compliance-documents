---
title: "Remote Work / WFH Security Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-011"
version: "1.0.0"
status: "Draft"
owner: "Security Engineering Lead"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ./Endpoint-Security-Policy.md
  - ../standards/Workstation-Baseline.md
  - ./Data-Classification-and-Handling-Policy.md
references:
  - ISO/IEC 27002:2022 (teleworking)
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Remote Work / WFH Security Policy |
| Document ID | GRS-ISMS-POL-011 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Engineering Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define security requirements for remote work to protect GridSite information and systems when accessed
outside corporate offices and NOCs.

## 2. Scope

All personnel performing work offsite, including home offices and coworking spaces.

## 3. Policy Statements

Company‑owned endpoints must be used for INTERNAL and RESTRICTED information and must comply with the
Workstation Baseline (Azure AD join, encryption, EDR, patching, iDrive360 backups). BYOD may access only
PUBLIC and CONFIDENTIAL information. Remote connections use Microsoft 365 SSO; direct inbound RDP/SSH
from the internet is prohibited. Network connections should be wired when practical; otherwise, use secure
Wi‑Fi with modern encryption (prefer UniFi Identity one‑click in offices/coworking). Users must prevent
shoulder surfing and secure physical documents; screen locks engage when unattended. Storage of company
data on personal cloud accounts or unmanaged storage is prohibited. All incidents or suspected compromise
of remote devices must be reported immediately.

## 4. Exceptions

Exceptions require risk assessment, approvals, and compensating controls.

## 5. Compliance Measurement

Measured via device compliance posture, access logs, and periodic audits.

## 6. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial WFH security policy aligned to workstation baseline and labels. |


