---
title: "Remote Access Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-062"
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
  - ./Authentication-and-MFA-Policy.md
  - ./Identity-and-Access-Management-Policy.md
  - ../standards/Identity-and-PAM-Standard.md
  - ../standards/Network-Segmentation-Standard.md
  - ../standards/Server-Baseline.md
references:
  - ISO/IEC 27002:2022 (remote working, access control)
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Remote Access Policy |
| Document ID | GRS-ISMS-POL-062 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Operations Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define secure remote access to GridSite systems and data for workforce, administrators, and third parties.

## 2. Scope

All remote connections to corporate, SaaS, and GridColo environments including VPN, bastions, RDP, and SSH.

## 3. Policy Statements

Remote access must use strong authentication with MFA; Duo Security is mandatory for RDP and SSH. Windows
systems use Microsoft Entra ID; Linux systems use named non‑privileged accounts with sudo elevation. Admin
ingress is restricted to secure NOC networks or approved bastions; direct exposure to the internet is prohibited.
VPN access is role‑based with split‑tunneling disabled for administrative profiles. Access is time‑bound where
feasible, and sessions are logged/recorded for privileged operations. BYOD devices may not be used for
INTERNAL or RESTRICTED data access. Where systems cannot forward access logs, periodic manual export and
review are performed. Remote access configurations are reviewed at least quarterly and after significant changes.

## 4. Exceptions

Exceptions require Security Operations and ISMS approval with defined compensating controls.

## 5. Compliance Measurement

Measured via access log sampling, bastion records, VPN reports, and review attestations.

## 6. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial remote access policy. |


