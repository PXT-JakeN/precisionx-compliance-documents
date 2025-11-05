---
title: "Information Security Policy (ISMS Charter)"
doc_type: "Policy"
id: "GRS-ISMS-POL-001"
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
  - ../policies/Risk-Management-Policy.md
  - ../policies/Statement-of-Applicability.md
  - ../policies/Business-Continuity-Policy.md
  - ../policies/Access-Control-Policy.md
  - ../policies/Identity-and-Access-Management-Policy.md
  - ../policies/Authentication-and-MFA-Policy.md
  - ../standards/Workstation-Baseline.md
  - ../procedures/ISMS-Implementation-Procedure.md
references:
  - ISO/IEC 27001:2022 Clauses 4–10
  - ISO/IEC 27002:2022
  - ISO 22301:2019
  - AICPA SOC 2 (Security, Availability, Confidentiality)
iso_clauses: ["4","5","6","7","8","9","10"]
soc2_criteria: ["CC-Series: Security","A-Series: Availability","C-Series: Confidentiality"]
bcms_clauses: ["ISO 22301 Clauses 4–10"]
---

## 1. Purpose

This policy establishes GridSite’s Information Security Management System (ISMS) objectives, scope,
governance, and principles. It codifies the organization’s commitment to protect the confidentiality,
integrity, and availability of information across corporate operations, SaaS platforms, colocation services,
and franchise programs, and to continually improve the ISMS in alignment with ISO/IEC 27001:2022,
ISO/IEC 27002:2022, ISO 22301:2019, and SOC 1/SOC 2.

## 2. Scope

This policy applies to GridSite Technology LLC and its operating subsidiaries, including GridSite Marketplace,
ComputeComplete, GridColo, the GridSite Real Estate Fund, and Powered by GridSite franchise/white‑label
programs. The ISMS covers all information assets, systems, infrastructure, and processes supporting business
operations and service delivery, whether hosted in public cloud, on managed customer sites, or at third‑party
facilities. It applies to all personnel with access to company information or systems, including employees,
contractors, vendors, and franchise operators. Exceptions to scope or applicability shall be recorded in the
Statement of Applicability (SoA) with risk‑based justification and compensating controls.

## 3. Roles and Responsibilities

| Role | Responsibilities |
|------|------------------|
| Executive Management | Provide sponsorship, resources, and leadership; approve policy and objectives; review ISMS performance. |
| ISMS Manager | Coordinate ISMS implementation, risk management, audits, SoA, and continual improvement; chair management reviews as delegated. |
| Compliance Manager | Maintain compliance roadmap; integrate regulatory/contractual obligations; manage CAPA tracking and evidence. |
| Security Engineering Lead | Define security architecture and baselines; identity and access controls; crypto and key management. |
| Security Operations Lead | Operate logging/SIEM, detection/response, incident lifecycle, and continuous monitoring. |
| IT Operations Lead | Oversee change/release, configuration, backup/restore, and endpoint/server baselines. |
| BC/DR Lead | Conduct BIAs, maintain BCMS strategy, DR plans, exercises, and reporting. |
| Asset Owners | Classify assets, approve access, ensure control effectiveness for owned assets. |
| System/Service Owners | Maintain configurations, patching, and operational records; support audits. |
| HR | Ensure onboarding/offboarding, training, and disciplinary processes align with policy. |
| All Personnel | Comply with policy, complete training, and report suspected incidents or weaknesses. |

## 4. Policy Statements

### 4.1 Governance and Management Commitment

- The ISMS is established under the authority of Executive Management and overseen by an ISMS Steering
  Committee chaired by the Director of IT and supported by the Compliance Manager.
- A Change Advisory Board (CAB) shall review significant changes weekly; Management Reviews shall occur
  at least quarterly and include risk, audit, incident, objectives, metrics, and improvement actions.
- Management shall allocate sufficient budget, personnel, and tools to operate the ISMS and communicate
  responsibilities to all personnel.

### 4.2 Information Security Principles

- Confidentiality: Limit information access to authorized parties based on least privilege and business need.
- Integrity: Maintain accuracy and completeness through configuration management, change control,
  and validation.
- Availability: Ensure systems and data are available to meet operational and contractual commitments.
- Accountability: Assign ownership and ensure traceability via authentication, authorization, and audit logs.
- Resilience: Design for recovery and continuity through redundancy, DR planning, and testing.

### 4.3 Risk Management

- GridSite shall maintain an asset inventory with assigned owners and conduct risk assessments aligned
  to ISO 27005 and ISO 27001 Clause 6.
- Risk evaluation criteria, tolerance, and treatment options shall be defined; high residual risks require
  Executive approval; critical risks require immediate action or compensating controls.
- A risk register and SoA shall be kept current; treatment actions shall be tracked to closure in CAPA.

### 4.4 Asset Protection and Data Handling

- Information shall be classified as Public, Internal, Confidential, or Restricted with handling rules for
  storage, transmission, sharing, and disposal.
- Confidential and Restricted data shall be encrypted in transit and at rest using approved algorithms; device
  encryption is mandatory on endpoints and servers processing company data.
- Access to sensitive data shall be reviewed at least quarterly; ownership shall be validated periodically to
  prevent privilege creep.

### 4.5 Access Control and Identity Management

- All users shall authenticate via centralized identity with SSO and enforced MFA; access shall follow least
  privilege and segregation of duties.
- Privileged access shall be governed by a PAM framework with session recording and break‑glass controls;
  quarterly access reviews are mandatory for privileged and high‑risk entitlements.
- Third‑party and franchise access shall use federation or contractual CUECs defining required controls.

### 4.6 Secure Systems and Infrastructure

- Cloud environments shall follow a secure landing zone design with segmentation of management, control,
  and data planes; interconnects shall use encrypted tunnels.
- Systems shall adhere to CIS‑aligned baselines and be provisioned via Infrastructure‑as‑Code; vulnerability
  scanning and configuration drift detection shall be automated with remediation to defined SLAs.
- Network security shall follow default‑deny, segmentation, and shield internet‑facing services with WAF
  and rate limiting; centralized logging to SIEM is required for critical systems.

### 4.7 Incident Response and Business Continuity

- GridSite shall maintain incident response procedures covering preparation, detection, containment,
  eradication, recovery, and lessons learned, with playbooks for common scenarios (e.g., credential theft,
  ransomware, data breach).
- Evidence handling shall follow chain‑of‑custody practices; notifications shall meet legal/contractual duties.
- The BCMS shall maintain BIAs, strategies, DR plans, and exercise schedules; results shall drive CAPA.

### 4.8 Compliance, Training, and Continuous Improvement

- Internal audits and external assessments (ISO, SOC) shall validate control effectiveness; findings shall be
  tracked through CAPA to closure.
- Security awareness is mandatory at onboarding and annually, with role‑based training for technical teams;
  phishing simulations shall be conducted periodically.
- ISMS objectives and metrics shall be defined, measured, reviewed at least quarterly, and updated as needed.

## 5. Exceptions

Exceptions to this policy shall follow the Exception & Compensating Controls Procedure, including documented
risk assessment, approval by appropriate authority, defined compensating controls, and expiration/review dates.

## 6. Compliance Measurement

Compliance shall be measured via internal audits, continuous control monitoring, and management reviews.
Key records include the risk register, SoA, access review logs, change records, incident reports, training
completion, and backup/DR test results.

## 7. Enforcement

This policy is mandatory for all personnel and affiliates. Non‑compliance may result in disciplinary action up to
and including termination of employment or contract, and legal action where applicable. Suspected violations or
weaknesses shall be reported to IT or Compliance without delay.

## 8. Management Declaration

Executive leadership affirms commitment to establish, implement, maintain, and continually improve the ISMS
to support GridSite’s mission and stakeholder trust.

## 9. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.1   | 2025-11-05 |        | Added IAM and MFA cross-references to related documents. |
| 1.0.0   | 2025-11-05 |        | Comprehensive draft aligned to ISO/BCMS/SOC and repository standards. |
| 0.1.0   | 2025-11-05 |        | Initial skeleton created. |


