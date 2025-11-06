---
title: "SOC System Description – Vendor Network"
doc_type: "System Description"
id: "GRS-ISMS-SD-003"
version: "1.0.0"
status: "Draft"
owner: "Product Owner – Vendor Network"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ../standards/API-Security-Standard.md
  - ../standards/CI-CD-Security-Standard.md
  - ../plans/Network-and-Data-Flow-Diagrams.md
  - ../policies/Customer-Data-Handling-and-Confidentiality-Policy.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | SOC System Description – Vendor Network |
| Document ID | GRS-ISMS-SD-003 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Product Owner – Vendor Network |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. System Overview

Vendor Network is a SaaS platform connecting buyers with vetted service vendors, integrating onboarding, due diligence,
and engagement workflows. Hosted in cloud environments with segmented networking and secure tunnels to managed sites.

## 2. Boundaries & Components

Web/UI, backend APIs, workflow engine, data stores, document storage, identity federation (Microsoft 365 SSO via
OIDC/SAML), observability stack, CI/CD pipelines, and admin tools restricted to NOC ingress.

## 3. Control Environment Highlights

- AuthN/Z: Entra SSO/MFA; RBAC and SoD; Duo MFA for SSH/RDP.
- Data Protection: Classification per P06; encryption at rest/in transit; secrets in central vault; immutable backups
  with quarterly restore tests.
- Delivery & Change: CI/CD with signed artifacts and protected branches; change approvals.
- Logging/Monitoring: Centralized logging and time sync; manual evidence exports if forwarding is not available.

## 4. Subservices & Dependencies

Cloud providers, storage, IDP, e‑signature, and communication services; tracked in vendor register with monitoring.

## 5. Data Flows & Network

See Network & Data Flow Diagrams; default‑deny segmentation; WAF/rate‑limits for APIs.

## 6. Customer Responsibilities (CUECs)

Customer SSO/MFA, endpoint security, handling of exported reports, and incident contact maintenance.

## 7. Changes Since Last Period

Capture material architecture, control, or subservice changes for the period.


