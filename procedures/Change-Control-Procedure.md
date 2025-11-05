---
title: "Change Control Procedure"
doc_type: "Procedure"
id: "GRS-ISMS-PRC-007"
version: "1.0.1"
status: "Draft"
owner: "IT Operations Lead"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
related_documents:
  - ../policies/Change-and-Release-Management-Policy.md
  - ../policies/Risk-Management-Policy.md
  - ../policies/Logging-Monitoring-and-SIEM-Policy.md
  - ../procedures/Emergency-Change-Procedure.md
  - ../standards/CI-CD-Security-Standard.md
references:
  - ISO/IEC 27001:2022 Annex A (Change Management)
  - ISO/IEC 27002:2022 8.32 Change Management
  - AICPA SOC 2 TSC (CC8)
iso_clauses: ["8"]
soc2_criteria: ["CC8"]
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Change Control Procedure |
| Document ID | GRS-ISMS-PRC-007 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | IT Operations Lead |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define the end-to-end steps for requesting, assessing, approving, implementing, validating, and closing
changes to GridSite systems and services.

## 2. Scope

All changes affecting production or corporate systems, including infrastructure, network, application,
security controls, and CI/CD pipelines.

## 3. Prerequisites

- Current asset inventory and service ownership
- Defined change classification, risk criteria, and windows
- Access to ticketing system, CI/CD, monitoring, and communication tools

## 4. Roles and Responsibilities

| Role | Responsibilities |
|------|------------------|
| Requester | Submits change request with full details and evidence of testing. |
| Approver (Owner) | Reviews risk/impact; approves/denies; ensures SoD. |
| CAB | Reviews significant changes; confirms readiness and rollback. |
| Implementer | Executes steps per runbook; records outcomes. |
| Validator | Confirms success criteria and health checks post-change. |

## 5. Procedure

1. Submit Change Request (CR)
   Provide a complete record including title, description, scope, affected components, risk/impact, dependencies,
   test plan, backout plan, implementation plan, validation plan, schedule, approvers, and evidence links. Classify
   as Standard, Normal, or Emergency and assign an initial risk rating.
2. Review and Risk Assessment
   The owner/approver verifies completeness and assesses security, availability, and compliance impact. High‑risk
   changes are routed to Security Engineering for review; SoD is enforced for production access.
3. CAB Review (if required)
   Present the CR for discussion. The CAB confirms testing sufficiency, rollback feasibility, stakeholder
   communication, and monitoring plans before approving, denying, or deferring.
4. Scheduling and Communication
   Place the change in an approved window and notify stakeholders and customers as required; update any
   maintenance pages or status notifications.
5. Implementation
   Execute the runbook, capture logs and screenshots, coordinate with on‑call staff, and maintain a real‑time
   communication channel for awareness and escalation.
6. Validation and Monitoring
   Validate success criteria and monitor metrics and alerts during an observation period. Where pipeline or SIEM
   integrations are unavailable, retain exports or screenshots as evidence.
7. Closure and Documentation
   Update the CR with results, attach evidence, and close or create follow‑up actions and CAPA items as needed.
8. Post‑Implementation Review (if failed/major impact)
   Within five business days, conduct a PIR to document root cause, contributing factors, and CAPA; link to the
   risk register when appropriate.

## 6. Records

- Change requests with approvals, evidence, and outcomes
- CAB minutes and decisions
- PIR documents and CAPA tracking

## 7. Metrics

- Change failure rate, MTTR, emergency change percentage, lead time

## 8. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.1   | 2025-11-05 |        | Expanded narrative steps; clarified evidence when integrations are unavailable. |
| 1.0.0   | 2025-11-05 |        | Initial procedure for change control. |


