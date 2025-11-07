---
title: "Access Control Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-064"
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
  - ./Identity-and-Access-Management-Policy.md
  - ./Segregation-of-Duties-Policy.md
  - ../standards/Identity-and-PAM-Standard.md
  - ../procedures/Access-Provisioning-and-Deprovisioning-Procedure.md
references:
  - ISO/IEC 27001:2022 A.5, A.8; SOC 2 CC6/CC7
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Access Control Policy |
| Document ID | GRS-ISMS-POL-064 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | ISMS Manager |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Establish principles, roles, and minimum requirements for controlling access to information and systems.

## 2. Scope

All identities (human and service), devices, applications, and data repositories within ISMS scope.

## 3. Policy Statements

Access is granted based on least privilege and role‑based access control, aligned to the SoD Policy. Microsoft
365/Entra ID is the preferred identity provider; SAML/OIDC federation is required for third‑party systems where
supported. All privileged access requires MFA; administrative access to servers is brokered via NOC‑restricted
ingress and Duo‑protected RDP/SSH. Joiner/Mover/Leaver processes enforce timely provisioning and
deprovisioning; access reviews occur at least quarterly for privileged roles and semiannually for others. Service
accounts are minimized, scoped, rotated, and monitored; secrets are stored in the central vault. Shared utility
accounts require explicit business justification, named authentication to unlock, and session logging. Access
decisions and changes are logged; where logging cannot be forwarded, periodic manual export and review occur.

## 4. Exceptions

Exceptions require ISMS approval with defined expiry and compensating controls.

## 5. Compliance Measurement

Measured via access reviews, provisioning ticket sampling, PAM session records, and vault audit logs.

## 6. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial access control policy. |


