---
title: "Statement of Applicability (SoA)"
doc_type: "Record"
id: "GRS-ISMS-POL-004"
version: "1.0.1"
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
  - ./Information-Security-Policy.md
  - ./ISMS-Scope-and-Context-Policy.md
  - ./Risk-Management-Policy.md
  - ../procedures/Risk-Assessment-Procedure.md
  - ../standards/README.md
  - ../plans/Risk-Register.md
references:
  - ISO/IEC 27001:2022 Annex A (93 controls)
  - ISO/IEC 27002:2022
  - ISO 22301:2019 (continuity-related controls)
  - AICPA SOC 2 Trust Services Criteria
iso_clauses: ["Annex A"]
soc2_criteria: ["CC-Series","A-Series","C-Series"]
bcms_clauses: []
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Statement of Applicability (SoA) |
| Document ID | GRS-ISMS-POL-004 |
| Version | 1.0.1 |
| Status | Draft |
| Owner | ISMS Manager |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |
| Classification | Internal – Controlled |
| Organization | GridSite Technology LLC and its operating subsidiaries |

## 1. Purpose

This Statement of Applicability identifies the ISO/IEC 27001:2022 Annex A controls applicable to GridSite’s
ISMS, records inclusion/exclusion decisions with rationale, assigns ownership, and links to implementation
and evidence. It is maintained as the authoritative mapping between assessed risks and selected controls.

## 2. Method and Scope

- Control applicability is determined by risk assessments (see ../procedures/Risk-Assessment-Procedure.md),
  ISMS scope and context, legal/contractual obligations, and business/technical architecture.
- Each control’s status is set to Included, Excluded, or Not Applicable (N/A). Exclusions/N/A require explicit
  risk-based justification and approval by Executive Management when residual risk is High.
- Evidence locations shall point to current records (tickets, configs, screenshots, exports) in approved systems.

## 3. Control Mapping Table (ISO/IEC 27001:2022 Annex A)

| Control ID | Control Name | Status (Included/Excluded/N/A) | Rationale (incl. risk ref) | Control Owner | Implementation Reference | Evidence Location | Notes |
|------------|--------------|--------------------------------|----------------------------|---------------|--------------------------|-------------------|-------|
|            |              |                                |                            |               |                          |                   |       |

Legend and guidance
- Status: “Included” when control is implemented; “Excluded/N/A” requires robust rationale tied to scope and risk.
- Rationale: Reference risk IDs from ../plans/Risk-Register.md where applicable.
- Implementation Reference: Link to relevant policies, standards, procedures, and system configs.
- Evidence Location: Link to specific records (e.g., SIEM dashboards, access review logs, change approvals).

## 4. Seed Entries (to be validated)

The following initial entries reflect Day 0–30 priorities and SHALL be validated during Management Review
before finalization.

| Control ID | Control Name | Status | Rationale (incl. risk ref) | Control Owner | Implementation Reference | Evidence Location | Notes |
|------------|--------------|--------|----------------------------|---------------|--------------------------|-------------------|-------|
| A.5.x | Information security policies | Included | Governance requirement; baseline ISMS policy set | ISMS Manager | ./Information-Security-Policy.md; ./ISMS-Scope-and-Context-Policy.md | Policy approvals; revision history | Use 27002 mapping when finalized |
| A.5.x | Roles and responsibilities | Included | Defines accountability and ownership | ISMS Manager | ./Information-Security-Policy.md §3 | Org chart; RACI tables | Align to WRITING-PLAN roles |
| A.5.x | Segregation of duties | Included | Prevent fraud/error; SoD risks | IT Operations Lead | ./policies/Segregation-of-Duties-Policy.md | Access matrix; approval logs | Prioritize high-risk roles |
| A.5.x | Contact with authorities | Included | Legal/regulatory obligations | Compliance Manager | ./policies/Incident-Communications-and-PR-Policy.md | Notification records | Map to IR process |
| A.5.x | Risk management | Included | Core ISMS requirement | ISMS Manager | ./Risk-Management-Policy.md; ../procedures/Risk-Assessment-Procedure.md | Risk register; CAPA | Tie to KRIs/KPIs |
| A.8.x | Identity management | Included | Access risk | Security Engineering Lead | ./policies/Identity-and-Access-Management-Policy.md | IAM configs; access reviews | Federation/MFA |
| A.8.x | Authentication information | Included | Credential risks | Security Engineering Lead | ./policies/Authentication-and-MFA-Policy.md | MFA settings; password policy | 
| A.8.x | Access rights | Included | Least privilege | Security Operations Lead | ./policies/Access-Control-Policy.md | Quarterly reviews; tickets | 
| A.8.x | Logging and monitoring | Included | Threat detection | Security Operations Lead | ./policies/Logging-Monitoring-and-SIEM-Policy.md | SIEM dashboards; retention | 
| A.8.x | Change management | Included | Integrity risk | IT Operations Lead | ./policies/Change-and-Release-Management-Policy.md; ../procedures/Change-Control-Procedure.md | CAB records; change logs | 
| A.8.x | Backup | Included | Resilience | BC/DR Lead | ./policies/Backup-and-Restore-Policy.md; ../procedures/Backup-and-Restore-Procedure.md | Test logs; restore reports | 
| A.5/6/8 | Incident management | Included | Legal/contractual obligations | Security Operations Lead | ./policies/Incident-Response-Policy.md; ../procedures/IR-Runbook-General.md | Incident tickets; PIRs | 

Note: Control IDs above are placeholders pending final ISO Annex A mapping and shall be updated to correct
numbers/titles during the first Management Review session.

## 5. Exclusions Summary (if any)

| Control ID | Control Name | Exclusion/N/A Rationale | Approval (Name/Role/Date) | Compensating Controls | Review Date |
|------------|--------------|-------------------------|---------------------------|-----------------------|-------------|
|            |              |                         |                           |                       |             |

## 6. Maintenance and Approval

- This SoA shall be reviewed at least quarterly and upon significant change (scope, services, platforms, sites).
- Updates shall be approved by Executive Management upon recommendation of the ISMS Manager.
- Changes impacting control coverage shall be synchronized with the Risk Register, policies/standards, and
  procedures, with evidence links updated accordingly.

## 7. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.1   | 2025-11-05 |        | Added Document Control section; standardized header format. |
| 1.0.0   | 2025-11-05 |        | Initial SoA structure, guidance, and seed entries for Day 0–30. |


