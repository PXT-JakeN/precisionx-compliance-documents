---
title: "NOC Operations Manual"
doc_type: "Procedure"
id: "GRS-ISMS-PRC-034"
version: "1.0.0"
status: "Draft"
owner: "NOC Manager"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ../standards/NOC-Build-Standard.md
  - ../policies/Incident-Response-Policy.md
  - ../policies/Change-and-Release-Management-Policy.md
  - ../policies/Logging-Monitoring-and-SIEM-Policy.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | NOC Operations Manual |
| Document ID | GRS-ISMS-PRC-034 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | NOC Manager |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define day‑to‑day operations of the dual‑NOC model, including monitoring, communications, escalation, and
surge response.

## 2. Scope

Primary NOC (Plano, TX) and secondary geographically diverse NOC; support for offices and GridColo sites.

## 3. Roles & Shifts

NOC Supervisor, Monitoring Analyst, Incident Coordinator, Communications Liaison. Maintain 24x7 coverage with
documented handoffs and shift checklists.

## 4. Tooling & Communications

Operate SIEM, telemetry, ticketing, and paging. Maintain resilient Microsoft Teams AV bridge 24x7 between NOCs
with ability to add participants for surge and incident coordination; fallback to radio/SIP alerts per standard.

## 5. Monitoring & Triage

Use runbooks for alert triage; classify severities; engage on‑call; ensure logs/time sync; export evidence manually
if forwarding is not available.

## 6. Escalation & Incident Handling

Follow Incident Response Policy and playbooks; coordinate status page updates with Communications; record
timelines; conduct hotwash and PIR/CAPA.

## 7. Change, Maintenance, and Access

Schedule maintenance windows; enforce Change and Release policies; restrict administrative ingress to NOC
networks with Duo‑protected RDP/SSH; maintain bastions and jump hosts.

## 8. Surge Operations

Activate surge mode during major events; expand bridge participants; define roles for additional staff; maintain
rollup dashboards and event logs.

## 9. Records & Metrics

Shift logs, incident timelines, change windows, communications transcripts; measure MTTD/MTTR, escalations,
bridge uptime, and evidence completeness.

## 10. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial NOC operations manual. |


