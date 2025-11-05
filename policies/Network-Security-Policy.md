---
title: "Network Security Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-014"
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
  - ../standards/Network-Segmentation-Standard.md
  - ../standards/Firewall-and-WAF-Standard.md
  - ../standards/Logging-and-Time-Sync-Standard.md
  - ../standards/Server-Baseline.md
references:
  - ISO/IEC 27002:2022 (8.20)
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Network Security Policy |
| Document ID | GRS-ISMS-POL-014 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Engineering Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Set policy direction for segmentation, ingress/egress control, secure wireless, and monitoring across corporate,
cloud, and facility networks.

## 2. Scope

Corporate offices, NOCs, GridColo sites, and cloud virtual networks.

## 3. Policy Statements

GridSite segments networks into management, control, data, corporate, and guest zones with default‑deny
policies between zones. Administrative access to locally hosted servers is permitted only from secure NOC
networks and never from the internet or general corporate segments. Corporate wireless uses UniFi Identity
for one‑click authentication with strong encryption; guest and unmanaged networks are separated. Egress from
sensitive zones is restricted and logged. Network security events are centralized where possible; when not,
manual reviews and evidence capture are required.

## 4. Exceptions

Exceptions require risk assessment, approvals, and compensating controls with expiry, and are documented in
the exception register.

## 5. Compliance Measurement

Measured via rule reviews, segmentation validation, and egress control audits.

## 6. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial network security policy. |


