---
title: "Logging & SIEM Onboarding Procedure"
doc_type: "Procedure"
id: "GRS-ISMS-PRC-019"
version: "1.0.0"
status: "Draft"
owner: "Security Operations Lead"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
related_documents:
  - ../policies/Logging-Monitoring-and-SIEM-Policy.md
  - ../standards/Logging-and-Time-Sync-Standard.md
references:
  - ISO/IEC 27002:2022 (logging/monitoring)
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Logging & SIEM Onboarding Procedure |
| Document ID | GRS-ISMS-PRC-019 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Operations Lead |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Provide step‑by‑step instructions to onboard log sources to the SIEM, including time sync, parsing, detection
coverage, and evidencing. Where integration is not possible, define manual review cadence and evidence
capture.

## 2. Scope

Servers, endpoints, network devices, cloud audit logs, identity providers, applications, and facility systems.

## 3. Prerequisites

- Confirm ownership and data sensitivity of the source
- Ensure time synchronization to approved NTP
- Determine event schemas and expected volumes

## 4. Procedure

1. Request and Plan
   - Open onboarding ticket; record source type, owner, sensitivity, and goals.
2. Configure Source
   - Enable logging and secure forwarding; set retention; apply filtering if required.
3. Connect to SIEM
   - Configure connectors/agents; verify receipt; document schemas and fields.
4. Parsing and Normalization
   - Implement parsing rules; map to common fields; validate with samples.
5. Detections
   - Implement detections for priority use cases; test alerting and routing.
6. Dashboards and Reports
   - Create source health and security dashboards; define weekly/monthly reports.
7. Manual Review (if no integration)
   - Define review cadence, responsible role, checklist, and evidence capture (screenshots/exports).
8. Documentation
   - Update source inventory; store configs, parsing rules, and detection lists.
9. Handover
   - Notify stakeholders; add to runbooks; schedule periodic validation.

## 5. Records

Tickets, connector configs, parsing rules, detection lists, dashboards, and review evidence.

## 6. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial SIEM onboarding procedure. |


