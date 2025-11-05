---
title: "Authentication & Multi-Factor Authentication (MFA) Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-009"
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
  - ./Identity-and-Access-Management-Policy.md
  - ./Access-Control-Policy.md
  - ../standards/Server-Baseline.md
  - ../standards/Workstation-Baseline.md
  - ../procedures/Change-Control-Procedure.md
references:
  - ISO/IEC 27001:2022 Annex A (Access Control)
  - ISO/IEC 27002:2022 (User Authentication)
  - NIST SP 800-63B (Digital Identity Guidelines) – for reference
  - AICPA SOC 2 TSC (CC6)
iso_clauses: ["5","8"]
soc2_criteria: ["CC6"]
bcms_clauses: []
---

## 1. Purpose

Define mandatory authentication requirements, including the use of strong, phishing-resistant MFA for
access to GridSite systems, to reduce the risk of unauthorized access and credential compromise.

## 2. Scope

Applies to all interactive user access and administrative access to corporate and production systems, remote
access, VPNs, cloud consoles, SaaS admin portals, CI/CD, code repositories, and privileged actions.

## 3. Roles and Responsibilities

| Role | Responsibilities |
|------|------------------|
| Security Engineering Lead | Defines authentication standards, approved factors, and enforcement policies. |
| Security Operations Lead | Monitors auth events; configures detections and response for anomalies. |
| IT Operations Lead | Implements MFA integrations; manages break-glass accounts and rotations. |
| System/Service Owners | Enforce MFA on their platforms and validate compliance. |
| All Personnel | Use only approved factors and protect authenticators; report lost/stolen devices immediately. |

## 4. Policy Statements

### 4.1 MFA Requirement and Approved Factors

- MFA is required for all privileged access, remote access, and all access to production and sensitive systems.
- Approved factors: platform authenticator (FIDO2/WebAuthn), TOTP authenticator apps, and hardware tokens.
- SMS and email OTP are not permitted for privileged access and shall be phased out for standard access.

### 4.2 Enrollment and Recovery

- Users shall enroll at least two distinct MFA methods where feasible. Backup codes must be securely stored.
- Lost/stolen authenticators require immediate report; helpdesk identity proofing must precede factor reset.

### 4.3 Session Management and Risk-based Controls

- Sessions shall be time-bound with re-authentication for sensitive actions; step-up MFA shall be enforced for
  privilege elevation or access to Restricted data.
- Conditional access and risk signals (e.g., new device, location anomalies) shall trigger step-up or denial.

### 4.4 Service Accounts and Non-Interactive Access

- Service accounts shall not be used for interactive login. API access shall use tokens/keys bound to scopes
  and roles with rotation and least privilege. Where MFA is not feasible, additional controls (IP allowlists,
  short-lived credentials, workload identity) shall be enforced.

### 4.5 Break-Glass Accounts

- A minimal number of break-glass accounts may exist, stored in a secure vault, with enhanced monitoring,
  out-of-band MFA where feasible, and immediate rotation after emergency use. All use requires post-incident
  review and approval.

### 4.6 Password Standards (where passwords remain)

- Passwords shall meet complexity and length requirements aligned to NIST 800-63B (e.g., minimum length,
  deny lists for common/breached passwords). Password reuse across systems is prohibited.

### 4.7 Logging, Monitoring, and Evidence

- Authentication events shall be centralized in the SIEM; alerts shall detect brute-force, MFA fatigue, and
  impossible travel. Evidence of MFA enforcement and factor coverage shall be retained.

### 4.8 Exceptions

- Exceptions require documented risk assessment, approval by the Security Engineering Lead (and Executive
  Management for High residual risk), and compensating controls with expiry and review.

## 5. Compliance Measurement

Compliance shall be measured via MFA enrollment coverage, step-up enforcement rates, failed login trends,
and internal audit sampling of enrollment and reset processes.

## 6. Enforcement

Non-compliance may lead to access suspension and disciplinary action up to and including termination of
employment or contract.

## 7. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial comprehensive Authentication & MFA policy. |


