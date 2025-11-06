---
title: "Franchise Technical Baseline Standard"
doc_type: "Standard"
id: "GRS-ISMS-STD-020"
version: "1.0.0"
status: "Draft"
owner: "Franchise Program Director"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ./Facility-Physical-Security-Standard.md
  - ./NOC-Build-Standard.md
  - ./Network-Segmentation-Standard.md
  - ./Firewall-and-WAF-Standard.md
  - ./Workstation-Baseline.md
  - ./Server-Baseline.md
  - ./Backup-and-Immutability-Standard.md
  - ../policies/Facility-and-Franchise-Compliance-Policy.md
  - ../procedures/Franchise-Site-Onboarding-Procedure.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Franchise Technical Baseline Standard |
| Document ID | GRS-ISMS-STD-020 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Franchise Program Director |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define mandatory technical requirements for Powered by GridSite franchises and GridColo Inside locations to ensure
secure, resilient, and auditable operations aligned with GridSite standards and certifications.

## 2. Scope

Applies to all franchise‑operated facilities and systems that interconnect with GridSite cloud environments, NOCs,
and customer environments via secure tunnels.

## 3. Identity & Access

1. Microsoft Entra (M365) SSO is required for supported applications; SAML/OIDC federation must be used where
   available.
2. MFA is mandatory for all privileged access and any remote access; Duo MFA must be enforced for SSH and RDP.
3. Windows servers must join Entra ID; Linux access must use named, non‑privileged accounts with sudo for elevation.
4. Privileged sessions for infrastructure components must be recorded where feasible; logs retained per policy.

## 4. Network & Connectivity

1. Establish site‑to‑cloud secure tunnels using approved configurations; admin ingress to site workloads is limited to
   GridSite NOC networks.
2. Implement network segmentation per S04 with distinct zones (management, control/operations, tenant/data, guest).
3. Apply default‑deny firewall policy at zone boundaries; enable WAF protections for internet‑facing apps per S05.
4. Corporate Wi‑Fi must use UniFi Identity (or approved equivalent) with per‑user credentials and WPA2/WPA3‑Enterprise.
5. Workstations shall prefer wired connectivity; wireless permitted only on secured SSIDs bound to identity.

## 5. Endpoints & Servers

1. Workstations must comply with S01 (EDR, encryption at rest, CIS‑aligned hardening, automated patching, logging).
2. Servers must comply with S02 (minimal services, hardened SSH/RDP, centralized logging, time sync, backups).
3. BYOD devices may access only PUBLIC and CONFIDENTIAL data; INTERNAL/RESTRICTED data requires managed devices.

## 6. Site Access & Physical Security

1. Deploy the integrated access management portal and lobby kiosk at each site with three‑factor authentication
   (badge, face, PIN) and ID validation at enrollment.
2. Enforce background checks for facility staff/vendors; deny unescorted access while pending; maintain appeal
   workflow and audit logs.
3. Escort procedures must be enforced by kiosk with a maximum of five escortees per escort.
4. Guard terminal must provide fallback sign‑in with face/PIN; paper logs exist for contingency operations.
5. Exterior access permits entry to the lobby only until kiosk sign‑in; interior access is granted at sign‑in and
   automatically revoked at sign‑out.

## 7. Monitoring, Logging & Telemetry

1. Centralize logs for systems, access control, and critical applications; normalize time with approved NTP.
2. Where forwarding is not technically possible, perform scheduled manual exports to the evidence repository.
3. Implement DCIM telemetry with thresholds/alarms per S16; retain facility video and access logs per policy.

## 8. Backups & Recovery

1. Protect critical workloads with encrypted, immutable backups per S08; validate quarterly restores.
2. All workstations must register with iDrive360 (or successor) and meet backup success SLOs.
3. Maintain DR plans consistent with site roles; participate in BC/DR exercises and record results.

## 9. Change & Configuration Management

1. Use formal change control (P19/PR07/PR08) for site infrastructure changes; maintain asset/CMDB entries (R02).
2. Maintain baseline configurations as code where feasible; document deviations and approved exceptions per PR44.

## 10. Evidence & Compliance

1. Produce evidence for audits (access logs, change records, backups, training, vendor assessments) on request.
2. Where local systems cannot forward artifacts, export and archive manually to the designated evidence store.

## 11. Non‑Compliance

Sites that fail to meet this baseline shall implement compensating controls with approved exceptions and a remediation
timeline; repeat violations may result in suspension of connectivity until remediated.

## 12. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial franchise technical baseline standard. |


