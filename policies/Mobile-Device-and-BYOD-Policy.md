---
title: "Mobile Device & BYOD Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-013"
version: "1.2.0"
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
  - ./Data-Classification-and-Handling-Policy.md
  - ./Endpoint-Security-Policy.md
  - ./Remote-Work-Security-Policy.md
  - ../standards/Data-Loss-Prevention-Standard.md
  - ../standards/Workstation-Baseline.md
references:
  - ISO/IEC 27002:2022 (use of mobile devices and teleworking)
  - ISO/IEC 27001:2022 Annex A.6.7 (Remote working)
  - ISO/IEC 27001:2022 Annex A.7.9 (Security of assets off-premises)
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Mobile Device & BYOD Policy |
| Document ID | GRS-ISMS-POL-013 |
| Version | 1.2.0 |
| Status | Draft |
| Owner | ISMS Manager |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

This policy establishes requirements for the secure use of mobile devices and personally-owned (BYOD) equipment to protect GridSite information assets, networks, and services. It defines the responsibilities, security controls, and acceptable use requirements for all mobile and BYOD devices accessing company resources.

## 2. Scope

This policy applies to:

- All GridSite employees, contractors, vendors, and franchise personnel
- All mobile devices (smartphones, tablets, laptops) used to access GridSite information or services
- Both company-owned and personally-owned (BYOD) devices
- All GridSite operating subsidiaries including GridColo, GridSite Marketplace, Vendor Network, and ComputeComplete
- Powered by GridSite franchise and GridColo Inside white-label program participants

## 3. Definitions

| Term | Definition |
|------|------------|
| BYOD | Bring Your Own Device – the practice of using personally-owned devices for work purposes |
| MDM | Mobile Device Management – software for securing and managing mobile devices |
| SSO | Single Sign-On – authentication method allowing one set of credentials for multiple applications |
| MFA | Multi-Factor Authentication – requiring multiple verification methods to access resources |

## 4. Policy Statements

### 4.1 Company-Owned Device Requirements

Company-owned devices shall be configured and managed in accordance with the Workstation Baseline and Endpoint Security Policy, including:

- Full disk encryption enabled
- Screen lock with minimum 6-character PIN/password or biometric authentication
- Automatic screen lock after 2 minutes of inactivity
- Current operating system with all security patches applied
- Endpoint Detection and Response (EDR) agent installed and active
- Data Loss Prevention (DLP) controls enabled
- Mobile Device Management (MDM) enrollment completed

### 4.2 BYOD Access Restrictions

Personal BYOD devices (smartphones, tablets, and other personally-owned equipment) are permitted to access **only the following applications**:

| Permitted Application | Purpose |
|-----------------------|---------|
| Microsoft Teams | Collaboration and communication |
| Microsoft Outlook | Email and calendar access |

**All other corporate systems, applications, and data are prohibited from being accessed on BYOD devices.**

BYOD devices shall not be used to:

- Access the company intranet or internal portals
- Connect to internal file shares or document repositories
- Access line-of-business applications
- Store or download company files locally
- Access INTERNAL or RESTRICTED classified information

### 4.3 BYOD Security Model

GridSite does not require or enforce device-level security controls (such as passcodes, encryption, or MDM enrollment) on personally-owned BYOD devices. Instead, security is enforced at the application layer through Microsoft 365:

- **Authentication**: All access to Teams and Outlook requires Single Sign-On (SSO) with Multi-Factor Authentication (MFA) via Microsoft 365
- **Conditional Access**: Microsoft 365 Conditional Access policies control access based on user identity, location, and risk signals
- **Session Management**: Automatic session timeouts require re-authentication after periods of inactivity
- **Data Protection**: Microsoft 365 app protection policies prevent copying, saving, or forwarding corporate data to unauthorized locations

This approach ensures security is managed centrally through identity and access controls rather than relying on unenforceable device-level requirements.

### 4.4 Acceptable Use

#### 4.4.1 Permitted Activities on BYOD Devices

- Viewing and responding to corporate email in Microsoft Outlook
- Participating in Microsoft Teams chats, calls, and meetings
- Viewing shared files within the Teams or Outlook applications (view only, no local downloads)
- Accessing calendar and scheduling meetings

#### 4.4.2 Prohibited Activities on BYOD Devices

- Downloading or storing company files locally on the device
- Accessing any corporate systems beyond Teams and Outlook
- Email auto-forwarding to personal accounts
- Copying company data to personal cloud services (iCloud, Google Drive personal accounts, Dropbox)
- Sharing corporate data outside of approved Microsoft 365 applications
- Taking screenshots of sensitive business information
- Using personal devices in restricted areas where photography is prohibited

### 4.5 Data Classification on BYOD

| Data Classification | BYOD Access Permitted | Conditions |
|---------------------|----------------------|------------|
| PUBLIC | Yes | Via Teams/Outlook only |
| CONFIDENTIAL | Limited | View only via Teams/Outlook; no local storage |
| INTERNAL | No | Access only on company-managed systems |
| RESTRICTED | No | Access only on company-managed systems |

### 4.6 Incident Reporting and Response

#### 4.6.1 Reportable Events

The following must be reported to IT Security immediately:

- Lost or stolen device that has accessed company Teams or Outlook
- Suspected unauthorized access to corporate data
- Suspicious activity on company accounts

#### 4.6.2 Reporting Procedure

1. Contact the IT team immediately by creating a ticket at support@precisionx.tech
2. Provide device details and incident description
3. IT will revoke Microsoft 365 session tokens and require re-authentication
4. Complete incident report within 24 hours

#### 4.6.3 Lost or Stolen Devices

- Lost or stolen devices must be reported immediately
- IT Security will immediately revoke all active Microsoft 365 sessions for the user
- User must re-authenticate on all devices after session revocation
- Password reset may be required based on risk assessment

### 4.7 Termination and Offboarding

Upon separation from GridSite:

1. Microsoft 365 account access will be revoked immediately
2. All active sessions on personal devices will be terminated
3. Cached data in Teams and Outlook applications will become inaccessible
4. No device-level actions are required as no corporate data is stored locally

### 4.8 Privacy

#### 4.8.1 Company Rights

GridSite reserves the right to:

- Monitor access to corporate Microsoft 365 resources
- Revoke Microsoft 365 access at any time
- Enforce app protection policies that prevent data leakage

#### 4.8.2 Employee Privacy Protections

Since GridSite does not require MDM enrollment or device-level controls on BYOD devices:

- GridSite has no visibility into personal applications, photos, or data
- GridSite cannot remotely wipe or lock personal devices
- GridSite does not collect device location or hardware information
- Employee privacy on personal devices is fully preserved

### 4.9 Support Responsibilities

#### 4.9.1 IT Support Scope

IT Support will provide assistance for:

- Microsoft 365 account access and authentication issues
- Teams and Outlook application configuration
- MFA setup and troubleshooting

#### 4.9.2 Employee Responsibilities

Employees are responsible for:

- All device hardware, software, and maintenance
- Operating system updates and security
- Carrier and service plan costs
- Ensuring their personal device can run current versions of Teams and Outlook

## 5. Exceptions

Exceptions to this policy require ISMS Manager approval with documented compensating controls aligned to data classification. Exception requests must include:

- Business justification for expanded BYOD access
- Risk assessment
- Proposed compensating controls (may include MDM enrollment)
- Duration of exception
- Management approval

## 6. Compliance Measurement

Compliance with this policy is measured via:

- Microsoft 365 sign-in and access logs
- Conditional Access policy compliance reports
- App protection policy violation reports
- Security incident records

## 7. Enforcement

Violations of this policy may result in:

- Temporary suspension of BYOD privileges (Microsoft 365 access revocation)
- Permanent revocation of BYOD privileges
- Disciplinary action up to and including termination
- Legal action in cases of willful misconduct or data breach

## 8. Related Documents

- [Data Classification and Handling Policy](./Data-Classification-and-Handling-Policy.md)
- [Endpoint Security Policy](./Endpoint-Security-Policy.md)
- [Remote Work Security Policy](./Remote-Work-Security-Policy.md)
- [Data Loss Prevention Standard](../standards/Data-Loss-Prevention-Standard.md)
- [Workstation Baseline](../standards/Workstation-Baseline.md)

## 9. Revision History

| Version | Date       | Author       | Description |
|---------|------------|--------------|-------------|
| 1.0.0   | 2025-11-05 |              | Initial BYOD policy with label-based access limits. |
| 1.1.0   | 2026-01-13 | Jake Neal    | Major expansion: Added detailed device requirements, enrollment process, acceptable use guidelines, incident reporting, and privacy provisions. |
| 1.2.0   | 2026-01-13 | Jake Neal    | Simplified BYOD approach: Restricted BYOD access to Microsoft Teams and Outlook only. Removed device-level security requirements (passcodes, encryption, MDM) as they are unenforceable on personal devices. Security is now enforced through Microsoft 365 SSO/MFA and Conditional Access policies rather than device controls. This provides a practical, enforceable security model while preserving employee privacy on personal devices. |
