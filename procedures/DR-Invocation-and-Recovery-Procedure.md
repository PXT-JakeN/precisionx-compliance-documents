---
title: "DR Invocation & Recovery Procedure"
doc_type: "Procedure"
id: "GRS-ISMS-PRC-022"
version: "1.0.0"
status: "Draft"
owner: "BC/DR Lead"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
related_documents:
  - ../policies/Disaster-Recovery-Policy.md
  - ../standards/Backup-and-Immutability-Standard.md
  - ../procedures/IR-Runbook-General.md
references:
  - ISO 22301:2019
---

## Document Control

| Field | Value |
|-------|-------|
| Title | DR Invocation & Recovery Procedure |
| Document ID | GRS-ISMS-PRC-022 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | BC/DR Lead |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Provide stepwise guidance to declare a disaster, fail over services, and restore normal operations.

## 2. Scope

Applies to critical services and shared infrastructure identified in the BCMS.

## 3. Prerequisites

- Current contact lists and on‑call schedules
- Documented RTO/RPO and failover runbooks per service
- Verified backups and secondary region readiness

## 4. Procedure

1. Assess & Declare
   - Evaluate incident impact; if service disruption exceeds thresholds, the BC/DR Lead (or designee) declares
     DR and notifies stakeholders.
2. Activate Teams & Communications
   - Spin up DR bridge; add required personnel (including NOC AV link); initiate external comms if required.
3. Prepare for Failover
   - Freeze changes; confirm data replication and backup integrity; secure evidence.
4. Execute Failover
   - Follow service‑specific runbooks; update DNS/traffic routing; validate health checks.
5. Operate in DR Mode
   - Monitor capacity and error rates; prioritize critical transactions and customers.
6. Restore to Normal Operations
   - Plan and execute reversion when primary is healthy; reconcile data; validate RTO/RPO attainment.
7. Documentation & PIR
   - Record timelines, actions, and evidence; run PIR and track CAPA items.

## 5. Records

DR declarations, runbook steps, evidence of data integrity and timing, PIR and CAPA artifacts.

## 6. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial DR invocation and recovery procedure. |


