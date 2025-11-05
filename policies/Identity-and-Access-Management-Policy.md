---
title: "Identity & Access Management (IAM) Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-008"
version: "1.1.0"
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

## Document Control

| Field | Value |
|-------|-------|
| Title | Identity & Access Management (IAM) Policy |
| Document ID | GRS-ISMS-POL-008 |
| Version | 1.0.1 |
| Status | Draft |
| Owner | Security Engineering Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |
| Classification | Internal – Controlled |
| Organization | GridSite Technology LLC and its operating subsidiaries |

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

Identity creation, modification, and termination must follow an approved request with verifiable business
need and a unique identifier. When a person changes role or scope, their entitlements are adjusted within
three business days to maintain least privilege; involuntary terminations require same‑day revocation and
asset recovery checkpoints. All lifecycle events are captured in the ticketing system with approvers, time
stamps, and evidence of completion to enable audit sampling.

### 4.2 Authentication, Federation, and MFA

Microsoft 365 (Entra ID) is the authoritative identity provider for workforce identities and SSO. Where a
third‑party system supports federation, GridSite prefers SAML (or OIDC) integration to centralize
authentication and policy enforcement. All interactive access to corporate and production systems uses SSO
with enforced MFA as defined in the Authentication & MFA Policy. Shared accounts are prohibited except for
documented break‑glass scenarios; any break‑glass credentials are vaulted, monitored, and rotated immediately
after use. Local accounts on third‑party systems are permitted only when federation is not supported; such
cases require an approved exception with documented compensating controls and review dates.

### 4.3 Authorization, RBAC, and SoD

Access is granted using RBAC mapped to job functions with explicit segregation‑of‑duties constraints. High‑risk
SoD conflicts are cataloged and monitored; any unavoidable conflicts require management approval and
compensating controls. Temporary or elevated access is time‑bound and justified by ticket; just‑in‑time
elevation is preferred to reduce standing privilege.

### 4.4 Privileged Access Management (PAM)

Administrative actions are performed from named, MFA‑protected accounts. Where feasible, privileged
sessions are recorded and retained for investigations. Break‑glass procedures define who may authorize
emergency elevation, how activity is logged, and how post‑use review and rotation are executed. The
Privileged Accounts Register lists every admin identity with owner, scope, and last review date.

### 4.5 Service Accounts, API Keys, and Secrets

Non‑human identities (service accounts, workloads, CI/CD) are uniquely identified, tightly scoped, and rotated
per policy. Secrets are stored in approved vaults; hard‑coded credentials in source code or images are
prohibited. Keys and certificates are tracked in the Keys & Certificates Inventory with explicit expiry and
rotation cadences.

### 4.6 Access Provisioning and Reviews

Provisioning follows the Access Provisioning & Deprovisioning Procedure and requires documented approval
from the asset owner or delegate; any emergency access is regularized within one business day. Privileged and
high‑risk roles undergo quarterly reviews; standard roles are reviewed at least semiannually. Removals and
exceptions are evidenced for audit.

### 4.7 Federation and Third Parties

Third‑party and franchise access should be federated to Microsoft 365 wherever feasible. When federation is
not supported, contracts specify Complementary User Entity Controls and required attestations; local users
must meet MFA and credential hygiene requirements and be subject to periodic review.

### 4.8 Logging, Monitoring, and Evidence

Authentication and authorization events for critical systems are forwarded to the SIEM when supported.
Where systems cannot forward events, administrators perform documented manual reviews on a defined
cadence and retain screenshots or exports as evidence. Evidence of approvals, reviews, removals, and
exceptions is retained per the Records Management policy.

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
| 1.1.0   | 2025-11-05 |        | Incorporated Microsoft 365/SAML federation, manual log review fallback, and paragraph-based policy statements. |
| 1.0.1   | 2025-11-05 |        | Added Document Control section; standardized header format. |
| 1.0.0   | 2025-11-05 |        | Initial comprehensive IAM policy. |


