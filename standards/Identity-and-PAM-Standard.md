---
title: "Identity and Privileged Access Management (PAM) Standard"
doc_type: "Standard"
id: "GRS-ISMS-STD-006"
version: "1.0.0"
status: "Draft"
owner: "Security Engineering Lead"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
related_documents:
  - ../policies/Identity-and-Access-Management-Policy.md
  - ../policies/Authentication-and-MFA-Policy.md
  - ../standards/Server-Baseline.md
references:
  - ISO/IEC 27002:2022 (identity, access control)
  - AICPA SOC 2 (CC6)
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Identity and Privileged Access Management (PAM) Standard |
| Document ID | GRS-ISMS-STD-006 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Engineering Lead |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define enforceable requirements for identity lifecycle, federation, RBAC, SoD, and privileged access controls
across GridSite environments.

## 2. Scope

All identities (human and non‑human) and privileged operations.

## 3. Control Requirements

| Req ID | Requirement | Implementation | Evidence |
|--------|-------------|----------------|----------|
| IDP-01 | Entra SSO | Microsoft 365 SSO + MFA for workforce; SAML/OIDC federation for third‑party where supported | IdP configs |
| IDP-02 | JML | Timely joiner/mover/leaver updates; 24h (same‑day involuntary) | Tickets; logs |
| IDP-03 | RBAC & SoD | Role definitions; SoD matrix; no standing privilege where feasible | Role catalog; SoD matrix |
| IDP-04 | PAM | Named admin accounts; Duo MFA for SSH/RDP; session recording where feasible | PAM configs; logs |
| IDP-05 | Reviews | Quarterly privileged/high‑risk reviews; semiannual standard | Review records |
| IDP-06 | Service identities | Unique non‑human identities; least privilege; secret rotation | Vault/ACLs |
| IDP-07 | Exceptions | Document exceptions with compensating controls and expiry | Exception register |

## 4. Roles and Responsibilities

Security Engineering manages IdP and PAM platforms; IT Operations executes provisioning and reviews; GRC
tracks exceptions and evidence.

## 5. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial identity and PAM standard. |


