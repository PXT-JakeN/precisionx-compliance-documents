---
title: "Identity & Access Management (IAM) Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-008"
version: "1.0.0"
status: "Draft"
owner: "Security Engineering Lead"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ./Information-Security-Policy.md
  - ./Access-Control-Policy.md
  - ./Authentication-and-MFA-Policy.md
  - ./Segregation-of-Duties-Policy.md
  - ../procedures/Access-Provisioning-and-Deprovisioning-Procedure.md
  - ../procedures/Onboarding-and-Offboarding-Procedure.md
  - ../procedures/Change-Control-Procedure.md
  - ../plans/Access-Control-Matrix.md
  - ../plans/Privileged-Accounts-Register.md
  - ../plans/ISMS-Objectives-Register.md
references:
  - ISO/IEC 27001:2022 Annex A (A.5, A.6, A.8)
  - ISO/IEC 27002:2022 (Identity management, access control)
  - AICPA SOC 2 TSC (CC6 Access Controls)
iso_clauses: ["5","6","8"]
soc2_criteria: ["CC6"]
bcms_clauses: []
---

## 1. Purpose

Establish mandatory requirements for identity lifecycle and access control across GridSite’s environments to
ensure least privilege, segregation of duties, strong authentication, and timely revocation consistent with the
ISMS scope and applicable standards.

## 2. Scope

Applies to all identities (workforce, contractors, franchise users, vendors, service and machine accounts), all
GridSite-managed systems (cloud, SaaS platforms, endpoints, network, facilities), and all access methods
(interactive, API, automated jobs, break-glass).

## 3. Roles and Responsibilities

| Role | Responsibilities |
|------|------------------|
| Executive Management | Approves IAM policy, exceptions with significant risk, and resources. |
| Security Engineering Lead | Owns IAM architecture, RBAC models, federation, and technical controls. |
| Security Operations Lead | Monitors access events, enforces logging and alerting, supports investigations. |
| IT Operations Lead | Operates provisioning/deprovisioning processes and periodic access reviews. |
| System/Service Owners | Maintain role definitions and approvals for their systems; validate access reviews. |
| HR | Triggers joiner/mover/leaver events; ensures identity records accuracy. |
| All Personnel | Use access appropriately; protect credentials; report anomalies immediately. |

## 4. Policy Statements

### 4.1 Identity Lifecycle (Joiner/Mover/Leaver)

- Identities shall be created only upon approved requests with verified business need and unique identifiers.
- Role or job changes shall trigger access adjustments within 3 business days to maintain least privilege.
- Terminations and contract completions shall trigger deprovisioning within 24 hours (same-day for involuntary).
- All lifecycle events shall be recorded in ticketing systems with approvals and timestamps.

### 4.2 Authentication and MFA

- All interactive access to corporate and production systems shall use centralized identity with SSO and
  enforced MFA per the Authentication & MFA Policy.
- Shared accounts are prohibited except documented break-glass; credentials must be rotated after use.

### 4.3 Authorization, RBAC, and SoD

- Access shall be granted using role-based access control (RBAC) with roles mapped to job functions and
  SoD constraints. High-risk SoD conflicts shall be defined and monitored; compensating controls require
  documented approval.
- Temporary/elevated access shall be time-bound and justified; use just-in-time elevation where feasible.

### 4.4 Privileged Access Management (PAM)

- Administrative access shall be issued to named accounts, protected by MFA, and subject to session
  recording where feasible. Break-glass procedures must define authorization, logging, and post-use review.
- The Privileged Accounts Register shall be maintained with owners and last review dates.

### 4.5 Service Accounts, API Keys, and Secrets

- Non-human identities shall be uniquely identified, scoped to least privilege, and rotated per policy.
- Secrets (passwords, API keys, tokens) shall be stored in approved vaults; hard-coded secrets are prohibited.
- Keys and certificates shall be tracked in the Keys & Certificates Inventory with expiry and rotation.

### 4.6 Access Provisioning and Reviews

- Provisioning shall follow the Access Provisioning & Deprovisioning Procedure with documented approvals
  from asset owners or delegates. Emergency access requires retrospective approval within 1 business day.
- Access reviews shall occur at least quarterly for privileged and high-risk roles, and at least semiannually for
  standard roles; results and removals shall be evidenced.

### 4.7 Federation and Third Parties

- Where feasible, third-party and franchise access shall use identity federation; otherwise contracts shall
  specify Complementary User Entity Controls (CUECs) and required control attestations.

### 4.8 Logging, Monitoring, and Evidence

- Authentication and authorization events for critical systems shall be logged centrally; alerts shall be
  configured for anomalous activities (e.g., impossible travel, brute force, privilege escalation).
- Evidence of access approvals, reviews, and removals shall be retained per the Records Management policy.

### 4.9 Exceptions

- Exceptions to this policy require documented risk assessment, approval by the Security Engineering Lead
  (and Executive Management for High residual risk), and compensating controls with defined expiry.

## 5. Compliance Measurement

Compliance shall be measured via access review completion rates, privilege reduction metrics, failed login
and MFA challenge trends, and internal audit sampling of approvals and deprovisioning timeliness.

## 6. Enforcement

Non-compliance may lead to access suspension and disciplinary action up to and including termination of
employment or contract.

## 7. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial comprehensive IAM policy. |


