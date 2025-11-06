---
title: "SOC System Description – GridSite Marketplace"
doc_type: "System Description"
id: "GRS-ISMS-SD-001"
version: "1.0.0"
status: "Draft"
owner: "Product Owner – Marketplace"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ../policies/Information-Security-Policy.md
  - ../standards/Cloud-Landing-Zone-Standard.md
  - ../standards/API-Security-Standard.md
  - ../standards/CI-CD-Security-Standard.md
  - ../plans/Network-and-Data-Flow-Diagrams.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | SOC System Description – GridSite Marketplace |
| Document ID | GRS-ISMS-SD-001 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Product Owner – Marketplace |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. System Overview

GridSite Marketplace is a multi‑tenant SaaS enabling buyers and vendors to transact services. The platform operates in
cloud environments (Linode/DigitalOcean) with segmented VPCs/VNETs and secure tunnels to managed sites.

## 2. Boundaries & Components

Frontend, backend APIs, databases, object storage, identity provider integrations (Microsoft 365 SSO via OIDC/SAML),
observability (logs/metrics/traces), CI/CD pipeline, and administrative consoles restricted via NOC ingress.

## 3. Control Environment Highlights

- Identity & Access: Entra SSO/MFA; Duo MFA for SSH/RDP; RBAC and SoD enforced; service identities in vault with
  rotation.
- Data Protection: Encryption at rest and in transit; secrets in central vault; backups with immutability for critical
  data and quarterly restore tests.
- Change & Deployment: Branch protection, signed artifacts, isolated runners, and change approvals.
- Logging & Monitoring: Centralized logs/time sync; manual exports if forwarding unavailable; detections for auth and
  data access anomalies.

## 4. Subservices & Dependencies

Cloud providers (Linode/DigitalOcean), email/SMS gateways, payment processors, and analytics. Subservice oversight via
vendor register and assessments.

## 5. Data Flows & Network

Reference network/data‑flow diagrams. Default‑deny segmentation; WAF and rate limits per API standard.

## 6. Customer Responsibilities (CUECs)

Customer SSO/MFA, endpoint security, data classification, and incident communication contacts per CUEC template.

## 7. Changes Since Last Period

Capture material changes to architecture, controls, or subservices.


