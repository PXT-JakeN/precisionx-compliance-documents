---
title: "Privileged Access Elevation Procedure"
doc_type: "Procedure"
id: "GRS-ISMS-PRC-005"
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
  - ../policies/Privileged-Access-Management-Policy.md
  - ../standards/Identity-and-PAM-Standard.md
  - ../policies/Access-Control-Policy.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Privileged Access Elevation Procedure |
| Document ID | GRS-ISMS-PRC-005 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Engineering Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Provide a controlled, auditable process to grant time‑bound administrative access for operational needs and
incident response while minimizing risk.

## 2. Roles

Requester, Approver (system owner or delegate), Security Engineering, IT Operations, ISMS.

## 3. Prerequisites

Named user accounts; Duo‑protected RDP/SSH; Entra ID integration for Windows; sudo for Linux; central vault; PAM
session recording where feasible.

## 4. Procedure

1. Request: Submit ticket specifying scope, justification, duration, and approvals.
2. Verification: Confirm least privilege, SoD, and that a standard role cannot satisfy need; require MFA.
3. Enablement: Grant access via group membership, role assignment, or temporary credential from vault; limit to
   NOC‑restricted ingress and record sessions where supported.
4. Expiry & Revocation: Auto‑expire elevation; verify removal; rotate any issued secrets/keys.
5. Evidence & Review: Retain approvals and logs; where forwarding is not possible, export logs on cadence; review
   elevation activity weekly; investigate anomalies.

## 5. Records & Evidence

Tickets, approvals, role changes, PAM/session logs, vault audit logs.

## 6. Metrics

Elevations per period, average duration, exceptions, and anomaly rate.

## 7. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial privileged access elevation procedure. |


