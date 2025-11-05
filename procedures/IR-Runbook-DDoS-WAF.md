---
title: "IR Runbook – DDoS/WAF Evasion"
doc_type: "Procedure"
id: "GRS-ISMS-PRC-016"
version: "1.0.0"
status: "Draft"
owner: "SRE Lead"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ../standards/Firewall-and-WAF-Standard.md
  - ../standards/Network-Segmentation-Standard.md
  - ../policies/Incident-Response-Policy.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | IR Runbook – DDoS/WAF Evasion |
| Document ID | GRS-ISMS-PRC-016 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | SRE Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Coordinate mitigation when services experience volumetric or application‑layer attacks or WAF bypass.

## 2. Actions

1. Classify: Identify attack vectors, sources, and impacted endpoints.
2. Mitigate: Engage provider‑level DDoS defenses; tighten WAF rules; rate limit; enable bot protection.
3. Re‑route: Shift traffic, scale capacity, or enable maintenance banners as needed.
4. Validate: Monitor error budgets and latency; tune rules; avoid collateral damage.
5. Communicate: Update status page; coordinate with customers as needed; log all changes.
6. Post‑Event: Capture artifacts and update baselines and detections.

## 3. Records

WAF/firewall changes, provider tickets, telemetry snapshots, status updates.

## 4. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial DDoS/WAF runbook. |


