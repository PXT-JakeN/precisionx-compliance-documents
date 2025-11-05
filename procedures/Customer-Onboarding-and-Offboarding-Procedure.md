---
title: "Customer Onboarding & Offboarding Procedure"
doc_type: "Procedure"
id: "GRS-ISMS-PRC-028"
version: "1.0.0"
status: "Draft"
owner: "Customer Success Lead"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ../policies/Service-Continuity-for-SaaS-Policy.md
  - ../policies/Customer-Data-Handling-and-Confidentiality-Policy.md
  - ../policies/Privacy-and-Data-Protection-Policy.md
  - ../standards/SaaS-Multi-Tenancy-and-Isolation-Standard.md
  - ../standards/Identity-and-PAM-Standard.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Customer Onboarding & Offboarding Procedure |
| Document ID | GRS-ISMS-PRC-028 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Customer Success Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define steps to securely provision, operate, and decommission customer tenants and integrations while meeting
contractual, privacy, and continuity obligations.

## 2. Roles

Customer Success (lead), Account Manager, Security Engineering, SRE, Legal, Billing, ISMS.

## 3. Prerequisites

Executed agreement and NDA; configured SSO/SAML with Microsoft 365 preference; agreed data residency; runbook
contacts; support plan.

## 4. Procedure

1. Onboarding: Create tenant with least‑privilege defaults; enable SSO/MFA; apply data residency and DLP labels;
   provision secrets via vault; register log exports or manual export plan if forwarding is unavailable.
2. Controls & Access: Map roles to RBAC; restrict admin ingress to NOC/bastion; configure backups and monitoring.
3. Validation: Execute acceptance checklist (auth, audit, backups, alerts); capture evidence.
4. Change Management: Record enablement changes; coordinate releases per Release Management Procedure.
5. Offboarding: Confirm termination notice; export/return data per contract; disable identities; revoke access keys;
   destroy residual data after retention; capture certificates and logs.

## 5. Records & Evidence

Onboarding checklist, SSO configs, RBAC mappings, backup/monitoring confirmations, offboarding proof.

## 6. Metrics

Time‑to‑live, misconfiguration defects, offboarding SLA, data return timeliness.

## 7. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial customer onboarding & offboarding procedure. |


