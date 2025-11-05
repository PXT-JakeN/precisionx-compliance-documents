---
title: "Workforce Continuity Plan (Pandemic/Long Outage)"
doc_type: "Plan"
id: "GRS-ISMS-PLN-012"
version: "1.0.0"
status: "Draft"
owner: "HR Director"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ../policies/Business-Continuity-Policy.md
  - ../policies/Remote-Work-Security-Policy.md
  - ../standards/Workstation-Baseline.md
  - ../plans/Crisis-Management-Plan.md
  - ../plans/BCMS-Strategy-Plan.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Workforce Continuity Plan (Pandemic/Long Outage) |
| Document ID | GRS-ISMS-PLN-012 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | HR Director |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Ensure continuity of operations during pandemics and prolonged outages by enabling a hybrid, distributed workforce
with secure remote access, role coverage, and resilient communications.

## 2. Assumptions and Principles

Cloud‑first services in Linode/DigitalOcean, secure tunnels to managed/customer/franchise sites, dual‑NOC operations
linked by a persistent AV bridge for coordination and surge participation. Microsoft 365 SSO/SAML with MFA for apps,
Duo for SSH/RDP, wired workstation preference with UniFi Identity for secure Wi‑Fi, iDrive360 for endpoint backups,
and BYOD limits per P06 (PUBLIC/CONFIDENTIAL only on BYOD).

## 3. Activation and Objectives

Activate upon CMT declaration of a pandemic/long outage. Objectives: protect personnel, maintain critical services,
meet customer/regulatory obligations, and communicate status and guidance.

## 4. Workforce Strategies

Cross‑training and documented role coverage; remote‑work enablement with approved devices; hardware logistics and
spares; secure collaboration (Teams, M365), time‑boxed shifts; wellness and HR support; facility access via portal/
kiosk and guard terminal fallback for essential staff.

## 5. Technology Enablement

Hardened endpoints per S01; privileged access via P10 and S06; remote access via P62; backup and restore readiness per
S08/P25; logging/time sync per S07 with manual evidence exports if forwarding isn’t available.

## 6. Communications

NOC bridge active 24x7; radio/SIP alerts; crisis comms per PL06; customer status page updates; leadership briefings.

## 7. Exercising and Review

Annual exercise of workforce continuity scenarios; lessons learned to CAPA and plan updates; review after material
organizational or regulatory change.

## 8. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial workforce continuity plan. |


