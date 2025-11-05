---
title: "Privileged Access Management Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-010"
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
  - ./Identity-and-Access-Management-Policy.md
  - ./Authentication-and-MFA-Policy.md
  - ../standards/Identity-and-PAM-Standard.md
  - ../standards/Server-Baseline.md
references:
  - ISO/IEC 27002:2022 (identity & access control)
  - AICPA SOC 2 (CC6)
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Privileged Access Management Policy |
| Document ID | GRS-ISMS-POL-010 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Engineering Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Establish mandatory requirements for controlling privileged access, minimizing standing privileges, enforcing
MFA, and maintaining auditable records of administrative activity.

## 2. Scope

All privileged accounts and operations across servers, cloud control planes, network devices, applications, and
administrative tools.

## 3. Policy Statements

Privileged activity is performed from named accounts protected by MFA. Duo Security is required for SSH and
RDP interactive sessions. Where feasible, privileged sessions are recorded and periodically reviewed.
Administrative access to locally hosted servers is permitted only from secure NOC networks. Standing
privileges are minimized through role design and just‑in‑time elevation; shared accounts are prohibited except
approved break‑glass or utility cases per IAM policy. The Privileged Accounts Register lists all administrative
identities with owners and last review dates. Quarterly reviews confirm appropriateness; exceptions require
documented compensating controls and expiry.

## 4. Exceptions

Exceptions require risk assessment, approvals, and compensating controls with expiry and review.

## 5. Compliance Measurement

Measured via access review completion, session recording samples, and Duo coverage reports.

## 6. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial PAM policy aligned with Duo MFA and NOC ingress constraints. |


