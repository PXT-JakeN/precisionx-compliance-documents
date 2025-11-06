---
title: "SOC System Description – ComputeComplete & GridColo Services"
doc_type: "System Description"
id: "GRS-ISMS-SD-002"
version: "1.0.0"
status: "Draft"
owner: "Product Owner – ComputeComplete/GridColo"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ../standards/NOC-Build-Standard.md
  - ../standards/Facility-Physical-Security-Standard.md
  - ../standards/Cloud-Landing-Zone-Standard.md
  - ../plans/Network-and-Data-Flow-Diagrams.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | SOC System Description – ComputeComplete & GridColo Services |
| Document ID | GRS-ISMS-SD-002 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Product Owner – ComputeComplete/GridColo |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. System Overview

ComputeComplete provides managed compute and SaaS services; GridColo offers colocation facilities under the GridSite
Real Estate Fund. Operations are cloud‑first with secure site tunnels and dual‑NOC operations.

## 2. Boundaries & Components

Customer‑facing portals, management planes, hypervisor/VM layers, storage, network fabric, site DCIM, identity
integrations (Entra SSO/MFA), NOC tooling, and site access management with portal/kiosk and 3‑factor auth.

## 3. Control Environment Highlights

- Physical Security: Integrated access portal/kiosk, background checks for staff/vendors, escort limits, guard terminal
  fallback, audit logging.
- Identity & Access: NOC‑restricted admin ingress; Duo MFA for SSH/RDP; RBAC and privileged session recording.
- Data Protection & Backups: Encryption, vault‑managed secrets, immutable backups; quarterly restore tests.
- Monitoring & DCIM: Telemetry thresholds, alarms, and evidence exports if forwarding unavailable.

## 4. Subservices & Dependencies

Cloud providers, facility power/ISP providers, third‑party monitoring and ticketing platforms. Oversight via vendor
register and assessments.

## 5. Network & Data Flows

Segmented networks for management, control, and tenant data; secure ingress/egress; WAF and firewall standards applied.

## 6. Customer Responsibilities (CUECs)

Site access policies for customer personnel, endpoint security, and incident contacts; customer VPN or cross‑connect
management where applicable.

## 7. Changes Since Last Period

Capture material changes to architecture, controls, or subservices.


