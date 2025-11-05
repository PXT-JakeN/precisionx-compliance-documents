---
title: "Network Change Control Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-057"
version: "1.0.0"
status: "Draft"
owner: "Network Engineering Lead"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ./Change-and-Release-Management-Policy.md
  - ../procedures/Change-Control-Procedure.md
  - ../standards/Network-Segmentation-Standard.md
  - ../standards/Firewall-and-WAF-Standard.md
references:
  - ISO/IEC 27001:2022 A.8 (change management)
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Network Change Control Policy |
| Document ID | GRS-ISMS-POL-057 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Network Engineering Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Ensure network changes are planned, reviewed, authorized, implemented, and documented safely and
consistently across GridSite environments.

## 2. Scope

All configuration changes to network devices, firewalls/WAFs, VPNs, cloud networks, and site interconnects.

## 3. Policy Statements

Network changes follow formal change control with risk/impact assessment, rollback, and scheduling windows.
Default‑deny principles apply; rules must be specific, time‑bound when appropriate, and reviewed regularly.
Administrative access to network devices is restricted to secure NOC networks with MFA. Emergency changes are
allowed for restoration and require retrospective approval within one business day. All changes are logged and
backed up; where devices cannot forward logs, periodic manual exports and review are performed. Post‑change
validation confirms intended outcomes and no regression. Changes affecting security zones or internet exposure
require peer security review.

## 4. Exceptions

Exceptions require Network Engineering and ISMS approval with compensating controls.

## 5. Compliance Measurement

Measured via change record sampling, rule hygiene metrics, and config backup integrity checks.

## 6. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial network change control policy. |


