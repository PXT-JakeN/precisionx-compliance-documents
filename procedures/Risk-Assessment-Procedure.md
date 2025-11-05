---
title: "Risk Assessment Procedure"
doc_type: "Procedure"
id: "GRS-ISMS-PRC-002"
version: "1.0.1"
status: "Draft"
owner: "ISMS Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
related_documents:
  - ../policies/Risk-Management-Policy.md
  - ../policies/ISMS-Scope-and-Context-Policy.md
  - ../policies/Statement-of-Applicability.md
  - ../plans/Risk-Register.md
  - ../templates/_TEMPLATE-Procedure.md
references:
  - ISO/IEC 27001:2022 Clause 6 (Planning), Clause 8 (Operation)
  - ISO/IEC 27005:2018 Information Security Risk Management
  - AICPA SOC 2 Trust Services Criteria
iso_clauses: ["6","8"]
soc2_criteria: ["CC-Series"]
bcms_clauses: []
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Risk Assessment Procedure |
| Document ID | GRS-ISMS-PRC-002 |
| Version | 1.0.1 |
| Status | Draft |
| Owner | ISMS Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define the repeatable process for identifying, analyzing, evaluating, and treating information security risks
across the ISMS scope, producing updates to the Risk Register and Statement of Applicability (SoA).

## 2. Scope

Applies to enterprise risk assessments (annual), targeted assessments (significant changes), and ad-hoc
assessments triggered by emerging risks across corporate, SaaS, GridColo, and franchise contexts.

## 3. Prerequisites

- Current ISMS scope statement and interested parties register
- Up-to-date asset inventory and data classification
- Defined risk criteria, scales, and appetite (per Risk Management Policy)
- Access to evidence systems (ticketing, SIEM, IAM, CMDB)

## 4. Roles and Responsibilities

| Role | Responsibilities |
|------|------------------|
| ISMS Manager | Facilitates assessments; approves methodology; consolidates results; proposes SoA updates. |
| GRC Analyst | Coordinates workshops; documents scenarios; maintains Risk Register and evidence links. |
| Asset Owners | Provide asset context; validate risks; own treatment actions. |
| Control Owners | Propose/implement treatments; supply evidence; report effectiveness. |
| Executive Management | Approves high/critical risk acceptances and resources for treatment. |

## 5. Procedure

1. Initiate Assessment
   - Define assessment type (enterprise/targeted/ad-hoc), objectives, scope, and participants.
   - Confirm current scope, criteria, and appetite; schedule sessions.
2. Identify Assets and Scenarios
   - Enumerate in-scope assets and data; map to owners and classifications.
   - Identify threat events, vulnerabilities, and plausible scenarios (people, process, technology, third parties, facilities).
3. Analyze Risks
   - For each scenario, estimate likelihood and impact using approved scales; capture rationale and references.
   - Record inherent risk rating.
4. Evaluate Risks
   - Compare inherent ratings to risk criteria; determine need for treatment.
   - Propose control candidates (existing and new); reference ISO Annex A and current SoA.
5. Select Treatments and Plan
   - Choose treatment option (mitigate, accept, transfer, avoid).
   - Document treatment plan: actions, owner, target dates, resources, expected residual rating.
6. Record in Risk Register
   - Create/update entries with asset/scenario, ratings, treatments, status, evidence links.
   - Link related change tickets, access reviews, test results where applicable.
7. Update Statement of Applicability
   - Reflect control inclusion/exclusion changes with rationale, owners, implementation, and evidence.
8. Approvals and Communication
   - Obtain approvals for High/Critical residual risks from Executive Management.
   - Communicate assigned actions and due dates to owners; track via CAPA.
9. Monitor and Review
   - Review progress at least monthly; update statuses; verify evidence.
   - Present summary and KRIs in Management Review; adjust objectives as needed.

## 6. Records

- Risk Register entries with unique IDs and evidence links
- SoA updates with rationale and approvals
- Workshop materials (agendas, attendance) and outputs
- CAPA tracking for treatment actions

## 7. Metrics

- Time to close critical/high risks
- % of on-time treatment actions
- % access reviews completed on schedule
- Mean time to detect/respond (MTTD/MTTR) for security incidents related to top risks

## 8. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.1   | 2025-11-05 |        | Added Document Control section; standardized header format. |
| 1.0.0   | 2025-11-05 |        | Initial procedure established for enterprise and targeted assessments. |


