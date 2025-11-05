---
title: "Change & Release Management Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-019"
version: "1.1.0"
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
  - ./Information-Security-Policy.md
  - ./Risk-Management-Policy.md
  - ./ISMS-Scope-and-Context-Policy.md
  - ./Access-Control-Policy.md
  - ./Logging-Monitoring-and-SIEM-Policy.md
  - ../procedures/Change-Control-Procedure.md
  - ../procedures/Emergency-Change-Procedure.md
  - ../procedures/Release-Management-Procedure.md
  - ../standards/CI-CD-Security-Standard.md
references:
  - ISO/IEC 27001:2022 Annex A (Change Management)
  - ISO/IEC 27002:2022 8.32 Change Management
  - AICPA SOC 2 TSC (CC8 Change Management)
iso_clauses: ["8"]
soc2_criteria: ["CC8"]
bcms_clauses: []
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Change & Release Management Policy |
| Document ID | GRS-ISMS-POL-019 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | IT Operations Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |
| Classification | Internal – Controlled |
| Organization | GridSite Technology LLC and its operating subsidiaries |

## 1. Purpose

Establish mandatory controls for planning, assessing, approving, implementing, and validating changes and
releases across GridSite environments to protect service availability, integrity, and security.

## 2. Scope

Applies to infrastructure, platform, application, configuration, network, security, and schema changes across
corporate and production environments, including CI/CD pipelines and third-party managed components where
GridSite has responsibility or oversight.

## 3. Roles and Responsibilities

| Role | Responsibilities |
|------|------------------|
| Change Advisory Board (CAB) | Reviews significant changes weekly; ensures risk assessment, testing, and rollback. |
| IT Operations Lead | Owns change process; ensures records, approvals, and scheduling. |
| Security Engineering Lead | Reviews security-impacting changes; enforces SoD and approval criteria. |
| System/Service Owners | Authorize changes to owned systems; validate implementation and post-change checks. |
| Release Manager | Coordinates release windows, comms, and deployment readiness. |
| Compliance Manager | Verifies evidence completeness; samples changes for audit. |

## 4. Policy Statements

### 4.1 Change Classification and Records

Changes are classified as Standard, Normal, or Emergency. Each record contains a unique ID and required
fields including purpose, scope, risk/impact, test plan, backout plan, approvals, schedule, and evidence links.
Standard changes are pre‑approved when documented criteria, steps, and guardrails are in place; these are
periodically reviewed for accuracy and risk.

### 4.2 Risk and Impact Assessment

Non‑standard changes include a risk assessment covering security, availability, and compliance, with explicit
dependency analysis and customer/partner impact where applicable.

### 4.3 Testing, Segregation of Duties, and Approvals

Testing occurs in non‑production where feasible with predefined acceptance criteria. Production changes
follow segregation‑of‑duties; high‑risk changes use distinct requester, tester, and approver roles.

### 4.4 Scheduling and Communication

Production changes are scheduled in approved windows with stakeholder communication; customer
notifications are issued when required by contract or risk.

### 4.5 Implementation, Validation, and Monitoring

Implement per runbook, validate success criteria, and monitor for anomalies during an observation period.
Outcomes, issues, and corrective actions are documented in the record.

### 4.6 Emergency Changes

Emergency changes may be expedited to mitigate outages or risk; a retrospective CAB review occurs within
three business days with full documentation of approvals and outcomes.

### 4.7 Release Management and CI/CD

Release pipelines enforce code review, artifact integrity, environment promotion controls, and rollback. The
deployment automation captures logs and artifacts as audit evidence; where integration to SIEM is not
possible, administrators retain exports or screenshots per the Logging policy.

### 4.8 Records and Retention

- Change records, approvals, test evidence, and rollback outcomes shall be retained per Records Management
  requirements and made available for audits.

### 4.9 Metrics and Continuous Improvement

- Track change failure rate, mean time to restore, lead time for changes, and emergency change percentage;
  review trends in Management Review and drive improvements.

## 5. Exceptions

Exceptions require documented risk assessment, approval by IT Operations Lead (and Executive Management for
High residual risk), and compensating controls with defined expiry.

## 6. Compliance Measurement

Compliance shall be measured via change record sampling, CAB reviews, SoD checks, and CI/CD control tests.

## 7. Enforcement

Non-compliance may result in disciplinary action up to and including termination of employment or contract.

## 8. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.1.0   | 2025-11-05 |        | Expanded narrative sections; clarified evidence expectations when integrations are unavailable. |
| 1.0.0   | 2025-11-05 |        | Initial comprehensive Change & Release Management policy. |


