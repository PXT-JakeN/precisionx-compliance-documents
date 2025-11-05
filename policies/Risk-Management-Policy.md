---
title: "Risk Management Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-003"
version: "1.0.1"
status: "Draft"
owner: "Matt Jones, Director of IT"
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
  - ./Statement-of-Applicability.md
  - ../procedures/Risk-Assessment-Procedure.md
  - ../plans/Risk-Register.md
  - ../plans/ISMS-Objectives-Register.md
references:
  - ISO/IEC 27001:2022 Clauses 4, 6, 8, 9, 10
  - ISO/IEC 27005:2018 Information Security Risk Management
  - ISO 22301:2019 (business continuity risk considerations)
  - AICPA SOC 2 TSC (CC, A, C)
iso_clauses: ["4","6","8","9","10"]
soc2_criteria: ["CC-Series","A-Series","C-Series"]
bcms_clauses: ["ISO 22301 Clauses 4–10"]
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Risk Management Policy |
| Document ID | GRS-ISMS-POL-003 |
| Version | 1.0.1 |
| Status | Draft |
| Owner | Matt Jones, Director of IT |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |
| Classification | Internal – Controlled |
| Organization | GridSite Technology LLC and its operating subsidiaries |

## 1. Purpose

This policy establishes GridSite’s information security risk management framework, defining methodology,
evaluation criteria, appetite, treatment, and governance to identify, assess, and treat risks that may affect the
confidentiality, integrity, and availability of information assets within the ISMS scope.

## 2. Scope

This policy applies to all in-scope organizational entities, services, systems, processes, and locations defined
in the ISMS Scope & Context Policy, and to all personnel with risk-related responsibilities including employees,
contractors, and relevant third parties.

## 3. Roles and Responsibilities

| Role | Responsibilities |
|------|------------------|
| Executive Management | Approves risk appetite, high/critical risk acceptances, and resources for treatment. |
| ISMS Manager | Owns the risk methodology, criteria, and process; ensures periodic risk assessments occur. |
| Compliance Manager | Maintains risk register and evidence; aligns obligations (ISO/SOC/legal) in risk treatment. |
| Asset Owners | Identify and classify assets; assess risks; approve and track treatments for owned assets. |
| Control Owners | Implement and evidence controls; report effectiveness and residual risk. |
| System/Service Owners | Maintain configurations; support scanning, monitoring, and remediation. |
| BC/DR Lead | Ensures continuity risks are integrated with BIA/strategy and DR plans. |
| All Personnel | Report suspected risks, incidents, and control weaknesses.

## 4. Policy Statements

### 4.1 Risk Management Methodology

- GridSite shall maintain a documented risk management methodology aligned to ISO/IEC 27005 and ISO/IEC
  27001 Clause 6, covering risk identification, analysis, evaluation, treatment, acceptance, communication,
  and monitoring.
- Risk identification shall consider threats, vulnerabilities, likelihood, and impact across people, process,
  technology, suppliers, and facilities. Asset inventory and data classification are mandatory inputs.
- Analysis may use qualitative or semi-quantitative scales; evaluation shall compare results against defined
  risk criteria and appetite to determine treatment.

### 4.2 Risk Criteria and Appetite

- Risk criteria shall define likelihood and impact scales, scoring thresholds, and categorization (e.g., Low,
  Moderate, High, Critical) with alignment to contractual obligations and regulatory requirements.
- The organization’s risk appetite shall set tolerances for residual risk. Residual High risks require Executive
  approval; Critical residual risks require immediate action or compensating controls and time-bound review.

### 4.3 Risk Treatment and Options

- Acceptable treatment options: mitigate (implement/improve controls), accept (with approval), transfer
  (insurance/contract), or avoid (change scope/process). Selected treatments shall be proportionate to risk
  and business context.
- All treatment plans shall specify owner, actions, target dates, required resources, expected residual risk,
  and evidence of completion. Treatments shall be tracked to closure in the CAPA process.

### 4.4 Risk Register and Records

- GridSite shall maintain a centralized risk register as the system of record, including asset, scenario, initial
  rating, treatment plan, residual rating, owner, status, and evidence links.
- The register shall be reviewed at least quarterly by the ISMS Manager and reported to Management Review.

### 4.5 Statement of Applicability (SoA)

- The SoA shall map ISO/IEC 27002 controls to in-scope risks and environments and record inclusion/
  exclusion rationale, control ownership, implementation approach, and evidence locations.
- SoA updates shall follow risk assessment outcomes, new threats, or significant changes (e.g., services,
  platforms, facilities); changes shall be synchronized with procedures and standards.

### 4.6 Risk Assessment Cadence and Triggers

- Formal enterprise risk assessments shall occur at least annually and upon significant change (e.g., new
  product, major architecture change, new data category, acquisition, new facility, or franchise rollout).
- Targeted assessments shall be conducted for high-risk changes per the Change Control Procedure.

### 4.7 Monitoring, Metrics, and Reporting

- Key risk indicators (KRIs) and performance metrics (KPIs) shall be defined and monitored (e.g., time to
  remediate critical vulnerabilities, access review completion rates, backup restore success rates).
- Risk and control performance shall be reviewed in Management Review and drive continual improvement.

### 4.8 Third-Party and Subservice Risk

- Supplier and subservice risks shall be assessed during onboarding and periodically thereafter; due diligence
  and monitoring requirements shall be commensurate with risk tier and aligned to SOC carve-out/CUECs.

### 4.9 Integration with BCMS

- Risk scenarios with continuity implications shall inform the BCMS strategy, DR plans, and exercise design;
  BIA results shall feed impact scales and recovery objectives.

## 5. Exceptions

Exceptions to this policy shall follow the Exception & Compensating Controls Procedure, including documented
risk assessment, approval authority based on residual rating, compensating controls, and expiration dates.

## 6. Compliance Measurement

Compliance shall be measured via internal audits, risk register reviews, SoA updates, and continuous control
monitoring. Evidence includes risk registers, treatment plans, approvals, SoA entries, audit reports, and CAPA
records.

## 7. Enforcement

Non-compliance with this policy may result in disciplinary action up to and including termination of employment
or contract, and legal action where applicable.

## 8. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.1   | 2025-11-05 |        | Added Document Control section; standardized header format. |
| 1.0.0   | 2025-11-05 |        | Comprehensive draft establishing methodology, criteria, treatment, and governance. |
| 0.1.0   | 2025-11-05 |        | Initial skeleton created. |


