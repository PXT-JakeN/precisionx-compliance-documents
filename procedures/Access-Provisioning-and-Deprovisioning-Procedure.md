---
title: "Access Provisioning & Deprovisioning Procedure (JML)"
doc_type: "Procedure"
id: "GRS-ISMS-PRC-004"
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
  - ../policies/Identity-and-Access-Management-Policy.md
  - ../policies/Access-Control-Policy.md
  - ../standards/Identity-and-PAM-Standard.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Access Provisioning & Deprovisioning Procedure (JML) |
| Document ID | GRS-ISMS-PRC-004 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | ISMS Manager |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define consistent steps for Joiner, Mover, and Leaver events to ensure timely, authorized access changes aligned
to least privilege and SoD.

## 2. Roles

Hiring Manager, HR, System Owners, ISMS Manager, IT Operations, Security Engineering.

## 3. Prerequisites

Approved role definitions and access profiles; ticketing workflow; identity provider (Microsoft Entra ID), SSO
integrations, and vault.

## 4. Procedure

1. Joiner: HR initiates ticket; manager requests role‑based access; approvals captured. IT provisions accounts in
   Entra ID; enable SSO/SAML where supported; enforce MFA. Issue endpoints per Workstation Baseline.
2. Mover: Manager submits change; revoke obsolete entitlements; add new ones; validate SoD; re‑acknowledge
   policies. Rotate secrets if role change affects service accounts or vault paths.
3. Leaver: Immediate revocation of logical access; disable tokens, VPN, RDP/SSH Duo; collect assets; remove from
   groups; rotate affected secrets/keys; update access matrices.
4. Evidence: Store approvals, timestamps, and configuration logs; if systems cannot forward logs, export manually
   on cadence.
5. Reviews: Run quarterly privileged and semiannual standard access reviews; remediate exceptions.

## 5. Records & Evidence

Tickets, approvals, access matrices, directory and application audit logs.

## 6. Metrics

Provisioning/deprovisioning SLA adherence, orphaned account count, review closure time.

## 7. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial access provisioning & deprovisioning procedure. |


