---
title: "Business Continuity Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-023"
version: "1.0.0"
status: "Draft"
owner: ""
approver: ""
approval_date: ""
effective_date: ""
next_review_date: ""
related_documents:
  - ../plans/README.md
references: []
iso_clauses: []
soc2_criteria: []
bcms_clauses: []
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Business Continuity Policy |
| Document ID | POL-BCP |
| Version | 0.1.1 |
| Status | Draft |
| Owner |  |
| Program Manager |  |
| Approver |  |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Establish objectives, governance, and mandatory requirements to ensure continuity of critical operations and
timely recovery from disruptive events impacting GridSite’s services and obligations.

## 2. Scope

Applies to GridSite corporate functions, SaaS platforms, GridColo facilities, and Powered by GridSite
franchise operations within the ISMS/BCMS scope, including suppliers and subservices where continuity
obligations exist.

## 3. Roles and Responsibilities

| Role | Responsibilities |
|------|------------------|
| Executive Management | Approves BCMS policy/objectives; allocates resources; reviews performance. |
| BC/DR Lead | Owns BCMS strategy, BIAs, recovery plans, exercises, and reporting. |
| ISMS Manager | Ensures alignment between BCMS and ISMS risk management and objectives. |
| IT Operations Lead | Maintains recovery capabilities (backups, DR runbooks, capacity). |
| Communications Lead | Manages crisis communications per plan and legal requirements. |
| System/Service Owners | Maintain recovery procedures and configuration; support exercises. |

## 4. Policy Statements

### 4.1 Objectives and Metrics

- Define continuity objectives and metrics (e.g., RTO/RPO, maximum tolerable downtime) per function/service.
- Track exercise results, recovery times, and gaps; present to Management Review.

### 4.2 Business Impact Analysis (BIA)

- Conduct BIAs to identify critical activities, dependencies, and recovery requirements; review at least annually
  or upon significant change.

### 4.3 Continuity Strategies and Plans

- Select strategies (redundancy, multi-region architecture, alternate work locations, provider failover) based on
  BIAs and risk; maintain recovery plans and runbooks for critical services.

### 4.4 Backup and Restore

- Maintain encrypted, immutable backups for critical systems and data with tested restore procedures and
  defined recovery targets; see Backup & Restore Policy and Procedure.

### 4.5 Exercises and Testing

- Conduct tabletop and technical exercises (e.g., failover) per schedule; capture results and corrective actions in
  CAPA; validate restoration times and data integrity.

### 4.6 Crisis Management and Communications

- Establish roles, escalation, and external communications per Crisis Communications Plan; meet contractual
  and regulatory notification timelines.

### 4.7 Records and Maintenance

- Maintain BIAs, strategies, plans, exercise reports, and improvements; review this policy at least annually or upon
  material changes.

## 5. Exceptions

Exceptions require documented risk assessment, approval by Executive Management, and compensating controls.

## 6. Compliance Measurement

Compliance shall be measured via exercise completion, restore success rates, and review of BIAs and plans.

## 7. Enforcement

Non-compliance may result in disciplinary action up to and including termination of employment or contract.

## 8. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Comprehensive BCMS policy aligned with ISMS and DR requirements. |
| 0.1.1   | 2025-11-05 |        | Added Document Control section; standardized header format. |
| 0.1.0   | YYYY-MM-DD |        | Initial draft |


