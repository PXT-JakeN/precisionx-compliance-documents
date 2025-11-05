---
title: "ISMS Scope & Context Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-002"
version: "1.0.0"
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
  - ./Risk-Management-Policy.md
  - ./Statement-of-Applicability.md
  - ./Business-Continuity-Policy.md
  - ./Access-Control-Policy.md
  - ../procedures/ISMS-Implementation-Procedure.md
  - ../plans/ISMS-Objectives-Register.md
references:
  - ISO/IEC 27001:2022 Clause 4 (Context of the organization)
  - ISO/IEC 27001:2022 Clause 6 (Planning)
  - ISO/IEC 27005:2018 (Information security risk management)
  - ISO 22301:2019 Clauses 4–8 (Context, Leadership, Planning, Support, Operation)
  - AICPA SOC 2 Trust Services Criteria (Security, Availability, Confidentiality)
iso_clauses: ["4.1","4.2","4.3","4.4","6.1"]
soc2_criteria: ["CC-Series: Security","A-Series: Availability","C-Series: Confidentiality"]
bcms_clauses: ["ISO 22301 Clauses 4–8"]
---

## 1. Purpose

This policy defines GridSite’s organizational context, interested parties and their requirements, and the
formal scope and boundaries of the Information Security Management System (ISMS). It ensures that the
ISMS focuses on in-scope processes, systems, and locations and maintains traceable interfaces and
dependencies to external parties and subservice organizations.

## 2. Scope

This policy applies to GridSite Technology LLC and its operating subsidiaries, including but not limited to
GridSite Marketplace, ComputeComplete, GridColo and the GridSite Real Estate Fund, as well as Powered by
GridSite franchise and white-label programs operating under the GridSite certification umbrella.

## 3. Roles and Responsibilities

| Role | Responsibilities |
|------|------------------|
| Executive Management | Approves ISMS scope; provides resources; reviews ISMS performance and objectives. |
| ISMS Manager | Maintains this policy; facilitates context reviews; proposes scope updates; ensures interfaces are documented. |
| Compliance Manager | Captures interested-party requirements; maintains SoA traceability; coordinates audits. |
| Security Engineering Lead | Defines technical boundaries, landing zones, and trust boundaries across clouds and sites. |
| Security Operations Lead | Ensures logging, monitoring, and incident integration across in-scope systems. |
| IT Operations Lead | Maintains inventories, configuration baselines, and connectivity maps; documents dependencies. |
| Asset Owners | Confirm asset ownership, data classification, and inclusion within scope; approve interfaces. |

## 4. Policy Statements

### 4.1 Organizational Context (External and Internal Issues)

GridSite shall determine external and internal issues that are relevant to its purpose and affect its ability to
achieve the intended outcomes of the ISMS. These issues shall be reviewed at least annually and upon
significant change.

| Category | Issue | Description | Implications for ISMS |
|----------|-------|-------------|-----------------------|
| External | Regulatory and contractual obligations | ISO 27001, ISO 22301, SOC 1/2, privacy, customer SLAs, franchise agreements | Control selection, evidence, notifications, SoA justifications |
| External | Threat landscape | Cloud-focused threats, supply chain, ransomware, credential abuse | Logging depth, MFA, PAM, DR strategies |
| External | Data residency and sovereignty | Regional hosting constraints for certain customers | Hosting location controls, vendor selection |
| Internal | Operating model | Cloud-first, hybrid workforce, managed sites, NOC primary (Plano) and secondary | Identity federation, remote security, segmentation |
| Internal | Technology platforms | Two public cloud environments, secure tunnels to managed/customer sites | Landing zones, network controls, key management |
| Internal | Organizational growth | Franchise and white-label expansion | Standardized minimum controls; site onboarding audits |

### 4.2 Interested Parties and Requirements

GridSite shall identify interested parties relevant to the ISMS and their requirements. Requirements shall be
tracked and evidenced through mapped controls and procedures.

| Interested Party | Needs/Expectations | Obligations | Evidence |
|------------------|--------------------|-------------|---------|
| Customers | Protection of data; service availability; incident notification | Contracts, SLAs, DPAs | SLAs, IR reports, audit packages |
| Regulators/Authorities | Compliance with laws and regulations | Applicable laws and guidance | Policies, records, compliance assessments |
| Franchisees/Partners | Minimum control set; audit oversight | Franchise agreements | Site audit reports, conformance checklists |
| Cloud Providers | Acceptable use; shared responsibility | Provider terms | Architecture docs, cloud configs |
| Employees/Contractors | Clear responsibilities; secure access | Employment/contract terms | Training records, access logs |
| Auditors/Assessors | Accurate descriptions; evidence availability | ISO/SOC audit criteria | SoA, risk register, control evidence |

### 4.3 ISMS Scope Definition and Boundaries

GridSite shall define, maintain, and publish the ISMS scope as follows:

- Organizational entities in scope: GridSite Technology LLC and operating subsidiaries providing corporate
  services and the SaaS/colocation offerings; Powered by GridSite franchise operations under certification.
- Services and processes in scope: Governance, risk, compliance, product/platform engineering, operations,
  security operations, business continuity and disaster recovery, supplier management, facility security.
- Systems and infrastructure in scope: The two public cloud environments used for monitoring, management,
  and SaaS; associated interconnects to GridColo data centers and managed customer sites; NOC facilities.
- Personnel in scope: Employees, contractors, vendors, and franchise operators with access to company
  information or systems.

The scope shall be specific enough to reflect actual operations and sufficiently comprehensive to meet ISMS
objectives. Any exclusions shall not undermine the organization’s ability to meet the intended ISMS outcomes.

#### 4.3.1 Boundaries, Interfaces, and Dependencies

| Area | Boundary Description | Interfaces/Dependencies | Notes |
|------|----------------------|-------------------------|-------|
| Cloud Environment A | Management, control, and data planes with landing zone guardrails | Identity provider, logging/SIEM, key vault, CDN | Primary SaaS hosting |
| Cloud Environment B | Redundant region and services | Inter-region networking, backup/DR | Secondary/DR hosting |
| GridColo Sites | Power/cooling, physical access, CCTV, DCIM | Secure tunnels to clouds; NOC oversight | Facility controls per standards |
| Primary NOC (Plano) | Secure operations center | Corporate network, clouds, GridColo | Visitor/badge processes |
| Secondary NOC | Geographically diverse site | Corporate network, clouds | Continuity capability |
| Managed Customer Sites | Minimal on-prem; secure tunnels | Customer CUECs; provider contracts | Carve-outs documented in SOC |

### 4.4 Inclusion/Exclusion Rationale and SoA Linkage

- Inclusions shall be documented with reference to business processes, systems, and locations.
- Exclusions shall be risk-assessed and justified; residual risks, if any, shall be tracked and approved by
  Executive Management per the Risk Management Policy.
- The Statement of Applicability (SoA) shall map ISO/IEC 27002 controls to the in-scope environment and
  record inclusion/exclusion rationale, owners, and evidence locations.

### 4.5 Locations, Systems, and Accounts in Scope (Inventory Overview)

| Category | Item | Example Entries |
|----------|------|-----------------|
| Corporate/NOC | Offices, coworking (WFH), primary and secondary NOCs | Plano NOC; approved coworking; remote work under policy |
| Cloud | Accounts/subscriptions | Cloud A prod/non-prod; Cloud B prod/non-prod |
| Connectivity | Tunnels/links | Cloud-to-cloud; cloud-to-site; site-to-NOC |
| Platforms | Shared services | Identity provider; SIEM; secrets/key management |
| Applications | SaaS platforms | GridSite Marketplace; Vendor Network; ComputeComplete |

### 4.6 Risk Evaluation Criteria and Method

- Risk identification, analysis, and evaluation shall follow the Risk Management Policy and associated
  procedure. Criteria shall include likelihood and impact scales aligned to business context and contractual
  obligations. Risk acceptance thresholds and approval authorities shall be documented.

### 4.7 Documentation and Records

GridSite shall maintain the following artifacts and keep them current:

- ISMS Scope statement (this policy) and supporting context records
- Interested parties register and requirements mapping
- Asset inventory and data classification records
- Risk register and treatment plans; SoA with rationales and ownership
- Network and data flow diagrams for in-scope systems
- Evidence of periodic reviews and management approvals

### 4.8 Review and Maintenance

- This policy and the scope shall be reviewed at least annually and upon significant organizational, technical,
  or regulatory change (e.g., new platform, new site, material change in services, M&A, or franchise model).
- Changes shall be proposed by the ISMS Manager and approved by Executive Management. Resulting updates
  to the SoA, risk register, and other dependent documents shall be completed without undue delay.

## 5. Exceptions

Exceptions to this policy shall follow the Exception & Compensating Controls Procedure, including documented
risk assessment, approval by appropriate authority, compensating controls, and time-bound expiry.

## 6. Compliance Measurement

Compliance shall be measured through internal audits, continuous control monitoring, and management reviews.
Key evidence includes the interested parties register, inventory and classification records, scope statements,
SoA entries, and network/data flow diagrams.

## 7. Enforcement

This policy is mandatory for all personnel and affiliates. Non-compliance may result in disciplinary action up to
and including termination of employment or contract, and legal action where applicable.

## 8. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Comprehensive draft establishing context, interested parties, and scope. |


