---
title: "Change Control Procedure"
doc_type: "Procedure"
id: "GRS-ISMS-PRC-007"
version: "1.0.0"
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
   - Populate fields: title, description, scope, affected components, risk/impact, dependencies, test plan,
     backout plan, implementation plan, validation plan, schedule, approvers, evidence links.
   - Classify as Standard/Normal/Emergency; assign severity/risk rating.
2. Review and Risk Assessment
   - Owner/Approver validates completeness; assesses security/availability/compliance impact; seeks Security
     Engineering review for high-risk changes.
3. CAB Review (if required)
   - Present CR; confirm testing, rollback, comms, and monitoring plans; approve/deny/defer.
4. Scheduling and Communication
   - Schedule in approved windows; notify stakeholders/customers as required; update maintenance pages.
5. Implementation
   - Execute steps; capture logs/screenshots; coordinate with on-call; maintain comms channel.
6. Validation and Monitoring
   - Validate success criteria; monitor metrics and alerts for a defined observation period; record results.
7. Closure and Documentation
   - Update CR with outcomes; attach evidence; close or create follow-up actions.
8. Post-Implementation Review (if failed/major impact)
   - Conduct PIR within 5 business days; record root cause and CAPA; link to risk register if relevant.

## 6. Records

- Change requests with approvals, evidence, and outcomes
- CAB minutes and decisions
- PIR documents and CAPA tracking

## 7. Metrics

- Change failure rate, MTTR, emergency change percentage, lead time

## 8. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial procedure for change control. |


