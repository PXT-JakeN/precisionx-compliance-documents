---
title: "Continuous Control Monitoring (CCM) Procedure"
doc_type: "Procedure"
id: "GRS-ISMS-PRC-042"
version: "1.0.0"
status: "Draft"
owner: "ISMS Manager"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ../policies/Metrics-and-Continuous-Improvement-Policy.md
  - ../policies/Records-Management-and-Evidence-Policy.md
  - ../standards/Logging-and-Time-Sync-Standard.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Continuous Control Monitoring (CCM) Procedure |
| Document ID | GRS-ISMS-PRC-042 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | ISMS Manager |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define how GridSite continuously measures key controls, collects evidence, and alerts owners on deviations.

## 2. Roles

ISMS (owner), Control Owners, SecOps, SRE, IT Operations, Data Owners.

## 3. Prerequisites

Defined control catalog with metrics; data sources (SIEM, CMDB, scanners); dashboarding; evidence repository; plan
for manual evidence exports if forwarding is not available.

## 4. Procedure

1. Define Measures: For each key control, define metric, target, frequency, owner, and data source.
2. Collect Data: Automate collection; normalize timestamps (UTC); store raw artifacts and summaries.
3. Alert & Triage: Generate alerts on threshold breaches; assign to owners; open tickets; link compensating controls
   where needed.
4. Report: Publish weekly/monthly dashboards; feed results to management reviews and audits.
5. Improve: Propose CAPA for chronic gaps; validate remediation effectiveness; update measures.

## 5. Records & Evidence

Metric definitions, raw exports, dashboard snapshots, alerts/tickets, CAPA records.

## 6. Metrics

Coverage of automated measures, alert MTTR, percent controls meeting targets.

## 7. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial CCM procedure. |


