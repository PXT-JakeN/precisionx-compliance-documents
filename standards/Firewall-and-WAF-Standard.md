---
title: "Firewall and WAF Standard"
doc_type: "Standard"
id: "GRS-ISMS-STD-005"
version: "1.0.0"
status: "Draft"
owner: "Security Engineering Lead"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
related_documents:
  - ../policies/Change-and-Release-Management-Policy.md
  - ../procedures/Change-Control-Procedure.md
  - ./Network-Segmentation-Standard.md
references:
  - ISO/IEC 27002:2022 (8.20 Network security)
  - AICPA SOC 2 (CC6, CC7)
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Firewall and WAF Standard |
| Document ID | GRS-ISMS-STD-005 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Engineering Lead |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Specify rule hygiene, change control, and monitoring requirements for firewalls and web application firewalls
that protect GridSite networks and applications.

## 2. Scope

Perimeter firewalls, cloud security groups, host firewalls, and WAFs protecting internet‑facing services.

## 3. Control Requirements

| Req ID | Requirement | Implementation | Evidence |
|--------|-------------|----------------|----------|
| FW-01 | Default deny | Block by default; allow least‑privilege rules only | Rule sets; audits |
| FW-02 | Rule hygiene | Use explicit sources/destinations/ports; expire temporary rules; review quarterly | Rule reviews; tickets |
| FW-03 | Change control | Apply PR07; require risk/impact, rollback, and approvals | Change records |
| FW-04 | Logging | Log accepts/denies for sensitive zones; centralize where possible; manual reviews if not | Logs; review records |
| FW-05 | WAF baselines | Enable OWASP CRS‑style protections; tune false positives; version controls | WAF configs; tuning notes |
| FW-06 | Monitoring & alerts | Detect rule drifts, open ports, and WAF anomalies; page on-call | Alerts; incidents |
| FW-07 | External exposure | Inventory and justify all public‑facing services; protect with WAF or equivalent | Inventory; diagrams |

## 4. Roles and Responsibilities

Security Engineering defines rule standards and reviews changes. IT Operations executes changes and maintains
documentation and evidence.

## 5. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial firewall and WAF standard. |


