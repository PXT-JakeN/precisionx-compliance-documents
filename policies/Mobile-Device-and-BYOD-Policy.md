---
title: "Mobile Device & BYOD Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-013"
version: "1.3.0"
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
| Version | 1.3.0 |
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
| APP | App Protection Policy – Microsoft Intune policies that protect corporate data at the application level without requiring device enrollment |
| MAM | Mobile Application Management – managing and securing applications on mobile devices without full device management |
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

### 4.2 BYOD Permitted Applications

Personal BYOD devices (smartphones and tablets) are permitted to access **only the following Microsoft 365 managed applications**:

| Permitted Application | Purpose |
|-----------------------|---------|
| Microsoft Outlook | Email and calendar access |
| Microsoft Teams | Collaboration and communication |
| Microsoft Word | Document viewing and editing |
| Microsoft Excel | Spreadsheet viewing and editing |
| Microsoft PowerPoint | Presentation viewing and editing |
| Microsoft SharePoint | Document library access |

**All other corporate systems, applications, and data are prohibited from being accessed on BYOD devices.**

BYOD devices shall not be used to:

- Access the company intranet or internal portals outside of approved apps
- Connect to internal file shares or document repositories outside of SharePoint
- Access line-of-business applications
- Access INTERNAL or RESTRICTED classified information

### 4.3 BYOD Security Controls

GridSite enforces security on BYOD devices through **Microsoft Intune App Protection Policies (APP)**. These policies are applied at the application level and do not require full device enrollment, preserving employee privacy while protecting corporate data.

#### 4.3.1 App Protection Policies

Two Intune App Protection Policies are deployed to enforce security controls on personal devices:

| Policy | Target Platform | Managed Applications |
|--------|-----------------|---------------------|
| GridSite BYOD APP - iOS | Apple iOS | Outlook, Teams, Word, Excel, PowerPoint, SharePoint |
| GridSite BYOD APP - Android | Google Android | Outlook, Teams, Word, Excel, PowerPoint, SharePoint |

#### 4.3.2 PIN Requirements

All managed applications on BYOD devices require a **6-digit numeric PIN** to access corporate data:

- PIN is required when opening any managed application
- PIN is required after **30 minutes of inactivity**
- PIN is specific to managed apps and separate from the device PIN
- Biometric authentication (Face ID, Touch ID, fingerprint) may be used in place of PIN after initial setup

#### 4.3.3 Data Loss Prevention Controls

The following data protection controls are enforced by the App Protection Policies:

| Control | Setting |
|---------|---------|
| Copy/paste to unmanaged apps | Blocked |
| Save copies to unmanaged locations | Blocked |
| "Save As" to personal storage | Blocked |
| Share to unmanaged apps | Blocked |
| Cut/copy character limit for unmanaged apps | 0 (fully blocked) |
| Printing | Allowed to managed printers only |
| Screen capture | Allowed (data is protected by copy restrictions) |

Data can only be shared between managed Microsoft 365 applications. Copying or pasting corporate data to personal apps, notes, messages, or other unmanaged applications is technically blocked by policy.

#### 4.3.4 Authentication Requirements

- **Authentication**: All access requires Single Sign-On (SSO) with Multi-Factor Authentication (MFA) via Microsoft Entra ID
- **Conditional Access**: Microsoft 365 Conditional Access policies control access based on user identity, location, and risk signals
- **Session Management**: In addition to the 30-minute app PIN timeout, Microsoft 365 session policies enforce re-authentication based on risk

### 4.4 Acceptable Use

#### 4.4.1 Permitted Activities on BYOD Devices

- Viewing and responding to corporate email in Microsoft Outlook
- Participating in Microsoft Teams chats, calls, and meetings
- Viewing and editing documents in Word, Excel, and PowerPoint
- Accessing SharePoint document libraries
- Accessing calendar and scheduling meetings
- Sharing files between managed Microsoft 365 applications

#### 4.4.2 Prohibited Activities on BYOD Devices

- Attempting to bypass App Protection Policy controls
- Saving corporate files to personal cloud storage (iCloud, Google Drive personal accounts, Dropbox)
- Copying corporate data to personal apps or messaging platforms
- Email auto-forwarding to personal accounts
- Using personal devices in restricted areas where photography is prohibited
- Jailbreaking or rooting devices (will trigger access block)

### 4.5 Data Classification on BYOD

| Data Classification | BYOD Access Permitted | Conditions |
|---------------------|----------------------|------------|
| PUBLIC | Yes | Via managed apps only |
| CONFIDENTIAL | Yes | Via managed apps only; copy/paste blocked |
| INTERNAL | No | Access only on company-managed systems |
| RESTRICTED | No | Access only on company-managed systems |

### 4.6 Incident Reporting and Response

#### 4.6.1 Reportable Events

The following must be reported to IT immediately:

- Lost or stolen device with managed Microsoft 365 apps installed
- Suspected unauthorized access to corporate data
- Suspicious activity on company accounts
- App Protection Policy errors or bypass attempts

#### 4.6.2 Reporting Procedure

1. Contact the IT team immediately by creating a ticket at support@precisionx.tech
2. Provide device details and incident description
3. IT will perform selective wipe of managed app data if necessary
4. Complete incident report within 24 hours

#### 4.6.3 Lost or Stolen Devices

- Lost or stolen devices must be reported immediately
- IT will immediately revoke all active Microsoft 365 sessions for the user
- IT can perform a **selective wipe** of only corporate data within managed apps without affecting personal data
- User must re-authenticate and re-enter app PIN on all devices after session revocation
- Password reset may be required based on risk assessment

### 4.7 Termination and Offboarding

Upon separation from GridSite:

1. Microsoft 365 account access will be revoked immediately
2. All active sessions on personal devices will be terminated
3. Selective wipe will remove corporate data from managed apps
4. Personal data, photos, and apps on the device are not affected

### 4.8 Privacy

#### 4.8.1 Company Rights

GridSite reserves the right to:

- Monitor access to corporate Microsoft 365 resources
- Revoke Microsoft 365 access at any time
- Enforce App Protection Policies that prevent data leakage
- Perform selective wipe of corporate data within managed applications

#### 4.8.2 Employee Privacy Protections

Since GridSite uses App Protection Policies (not full MDM enrollment) on BYOD devices:

- GridSite has no visibility into personal applications, photos, or data
- GridSite cannot remotely wipe or lock the entire device
- GridSite does not collect device location or hardware information beyond basic compliance checks
- Only corporate data within managed apps can be wiped; personal data is unaffected
- Employee privacy on personal devices is preserved

#### 4.8.3 Data Collected by App Protection Policies

The following limited information is collected for compliance monitoring:

- Device platform (iOS or Android)
- App versions of managed applications
- Compliance status with App Protection Policy
- Jailbreak/root detection status

### 4.9 Support Responsibilities

#### 4.9.1 IT Support Scope

IT Support will provide assistance for:

- Microsoft 365 account access and authentication issues
- Managed app installation and configuration
- App PIN setup and reset
- MFA setup and troubleshooting

#### 4.9.2 Employee Responsibilities

Employees are responsible for:

- All device hardware, software, and maintenance
- Operating system updates and security
- Carrier and service plan costs
- Installing managed apps from official app stores (Apple App Store, Google Play Store)
- Remembering their app PIN

## 5. Exceptions

Exceptions to this policy require ISMS Manager approval with documented compensating controls aligned to data classification. Exception requests must include:

- Business justification for expanded BYOD access
- Risk assessment
- Proposed compensating controls
- Duration of exception
- Management approval

## 6. Compliance Measurement

Compliance with this policy is measured via:

- Microsoft Intune App Protection Policy compliance reports
- Microsoft 365 sign-in and access logs
- Conditional Access policy compliance reports
- App protection policy violation reports
- Security incident records

## 7. Enforcement

Violations of this policy may result in:

- Temporary suspension of BYOD privileges (selective wipe and access revocation)
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
| 1.2.0   | 2026-01-13 | Jake Neal    | Simplified BYOD approach: Restricted BYOD access to Microsoft Teams and Outlook only. Security enforced through Microsoft 365 SSO/MFA and Conditional Access policies. |
| 1.3.0   | 2026-01-13 | Jake Neal    | Expanded managed apps to include Word, Excel, PowerPoint, and SharePoint. Implemented Microsoft Intune App Protection Policies for iOS and Android requiring 6-digit app PIN, 30-minute inactivity timeout, and copy/paste restrictions. Added selective wipe capability for offboarding. |
