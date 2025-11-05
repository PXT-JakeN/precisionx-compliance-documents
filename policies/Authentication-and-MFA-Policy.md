---
title: "Authentication & Multi-Factor Authentication (MFA) Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-009"
version: "1.2.0"
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

## Document Control

| Field | Value |
|-------|-------|
| Title | Authentication & Multi-Factor Authentication (MFA) Policy |
| Document ID | GRS-ISMS-POL-009 |
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

MFA is mandatory for privileged access, remote access, and any access to production or sensitive systems.
Approved factors include phishing‑resistant platform authenticators (FIDO2/WebAuthn), TOTP apps, and
hardware tokens. SMS or email OTP are not permitted for privileged access and are being phased out for
standard access in favor of stronger factors.

### 4.2 Enrollment and Recovery

Users enroll at least two distinct MFA methods when feasible; recovery codes are stored securely. Lost or
stolen authenticators are reported immediately. Helpdesk resets require identity proofing and ticketed
approval.

### 4.3 Session Management and Risk-based Controls

Sessions are time‑bound with re‑authentication for sensitive operations. Step‑up MFA is enforced for privilege
elevation and access to Restricted data. Conditional access evaluates device, location, and behavioral risk to
trigger step‑up challenges or deny access.

### 4.4 Service Accounts and Non-Interactive Access

Service accounts are not used for interactive login. API access uses scoped tokens or keys with rotation and
least privilege. Where MFA is infeasible (e.g., non‑interactive jobs), additional controls such as IP allowlists,
short‑lived credentials, or workload identity are required.

### 4.5 Break-Glass Accounts
### 4.6 Duo for Administrative Protocols (SSH/RDP)

Interactive administrative access to servers via SSH and RDP is protected by Duo Security. Administrators
must enroll Duo factors and systems must be configured to enforce Duo MFA for these protocols. Where
integration is temporarily infeasible, an approved exception with compensating controls and a remediation
timeline is required.

Only a minimal number of break‑glass accounts exist and are stored in a secure vault. Their use is monitored,
protected by out‑of‑band factors where feasible, and followed by immediate credential rotation and
post‑incident review.

### 4.7 Password Standards (where passwords remain)

Where passwords persist, they meet NIST 800‑63B guidance including minimum length and checks against
common/breached password lists. Password reuse across systems is prohibited.

### 4.8 Logging, Monitoring, and Evidence

Authentication events are centralized in the SIEM when integrations exist. For systems that cannot forward
events, administrators perform documented manual reviews on a defined cadence and retain screenshots or
exports. Detections address brute force, MFA fatigue, impossible travel, and privilege elevation.

### 4.9 Exceptions

Exceptions require documented risk assessment, approval by the Security Engineering Lead (and Executive
Management for High residual risk), and compensating controls with explicit expiry and review.

## 5. Compliance Measurement

Compliance shall be measured via MFA enrollment coverage, step-up enforcement rates, failed login trends,
and internal audit sampling of enrollment and reset processes.

## 6. Enforcement

Non-compliance may lead to access suspension and disciplinary action up to and including termination of
employment or contract.

## 7. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.2.0   | 2025-11-05 |        | Required Duo MFA for SSH and RDP administrative sessions. |
| 1.1.0   | 2025-11-05 |        | Incorporated Microsoft 365 SSO preference, clarified manual review when logs cannot be forwarded, and expanded narrative sections. |
| 1.0.1   | 2025-11-05 |        | Added Document Control section; standardized header format. |
| 1.0.0   | 2025-11-05 |        | Initial comprehensive Authentication & MFA policy. |


