---
title: "Privileged Accounts Register"
doc_type: "Register"
id: "GRS-ISMS-REG-005"
version: "1.0.0"
status: "Draft"
owner: "Security Operations Lead"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ../policies/Privileged-Access-Management-Policy.md
  - ../standards/Identity-and-PAM-Standard.md
  - ../procedures/Privileged-Access-Elevation-Procedure.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Privileged Accounts Register |
| Document ID | GRS-ISMS-REG-005 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Operations Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Track and govern privileged identities across systems to enforce least privilege, MFA, rotation, and oversight.

## 2. Required Fields

Account ID; system; type (break‑glass, service, admin); owner; justification; approval reference; MFA status; last
password/credential rotation; session recording enabled; last review date; exceptions link (if any); status.

## 3. Reviews and Maintenance

Monthly high‑risk review (cloud, prod DB, perimeter); quarterly full review; require Duo MFA for SSH/RDP and Entra ID
MFA for Windows; rotate service credentials per S09; export evidence when systems cannot forward.

## 4. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial privileged accounts register. |


