---
title: "Emergency Change Procedure"
doc_type: "Procedure"
id: "GRS-ISMS-PRC-008"
version: "1.0.0"
status: "Draft"
owner: "IT Operations Lead"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ../policies/Change-and-Release-Management-Policy.md
  - ../procedures/Change-Control-Procedure.md
  - ../standards/Firewall-and-WAF-Standard.md
  - ../standards/Network-Segmentation-Standard.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Emergency Change Procedure |
| Document ID | GRS-ISMS-PRC-008 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | IT Operations Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Provide a rapid, controlled process to implement changes required to restore service or remediate critical risk
while preserving auditability and safety.

## 2. Roles

Change Requester, Incident Commander, Approver-on-Call (CAB delegate), Implementer, ISMS observer.

## 3. Triggers

Active incident, critical security vulnerability, or imminent SLA/regulatory breach requiring immediate action.

## 4. Procedure

1. Declare Emergency: Link to incident ticket; document scope, risk, rollback. Notify CAB delegate/on-call.
2. Approve Quickly: Obtain verbal or electronic approval from delegate and system owner; record in ticket.
3. Implement Safely: Execute minimally scoped change; admin ingress via NOC/bastion only; MFA enforced (Duo for
   RDP/SSH). Take pre/post change snapshots/config backups.
4. Validate & Monitor: Confirm restoration; monitor telemetry and errors; roll back if adverse impact observed.
5. Close & Retrospective: Within 1 business day, present to full CAB for retrospective approval; attach evidence,
   logs, and timeline. Convert to standard change if follow-ups needed.

## 5. Records & Evidence

Incident and change tickets, approvals, config backups, logs, monitoring screenshots.

## 6. Metrics

Time-to-approval, change success rate, rollback rate, evidence completeness.

## 7. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial emergency change procedure. |


