---
title: "Mobile Device & BYOD Policy"
doc_type: "Policy"
id: "GRS-ISMS-POL-013"
version: "1.1.0"
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
  - ../standards/Mobile-Device-Security-Standard.md
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
| Version | 1.1.0 |
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
| MAM | Mobile Application Management – software for managing and securing applications on mobile devices |
| Containerization | Technology that creates a secure, isolated workspace separating corporate and personal data on a device |
| Remote Wipe | The capability to erase data from a device remotely |
| Jailbreaking/Rooting | Removing manufacturer security restrictions from a device, which is prohibited |

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

### 4.2 BYOD Eligibility and Enrollment

#### 4.2.1 Eligibility Requirements

- Employee must be in good standing with GridSite
- Role must be approved for BYOD participation by department manager and ISMS Manager
- Employee must complete BYOD security awareness training
- Device must meet minimum security specifications (Section 4.3)

#### 4.2.2 Enrollment Process

1. Submit BYOD enrollment request through the IT Service Portal
2. Review and sign the BYOD User Agreement
3. Schedule device configuration appointment with IT Support
4. Complete Mobile Device Management (MDM) or Mobile Application Management (MAM) enrollment
5. Receive confirmation of successful enrollment

### 4.3 BYOD Device Requirements

#### 4.3.1 Minimum Operating System Versions

| Device Type | Operating System | Minimum Version |
|-------------|------------------|-----------------|
| iOS Devices | iOS | 16.0 or later |
| Android Devices | Android | 13.0 or later |
| Windows Laptops | Windows | Windows 11 |
| macOS Devices | macOS | Ventura (13.0) or later |

#### 4.3.2 Required Security Controls

All enrolled BYOD devices must have:

- Device encryption enabled
- Screen lock with PIN/password (minimum 6 characters) or biometric authentication
- Automatic screen lock after 2 minutes of inactivity
- Up-to-date operating system with latest security patches
- Company-approved MDM/MAM solution installed and active
- Remote wipe capability enabled
- No jailbreaking, rooting, or unauthorized modifications

### 4.4 Data Access Restrictions

Personal BYOD devices are subject to data classification restrictions:

| Data Classification | BYOD Access Permitted | Conditions |
|---------------------|----------------------|------------|
| PUBLIC | Yes | No restrictions |
| CONFIDENTIAL | Yes | Via approved containerized applications only |
| INTERNAL | No | Access only on company-managed systems |
| RESTRICTED | No | Access only on company-managed systems |

INTERNAL and RESTRICTED information shall be accessed and processed solely on company-approved and managed systems.

### 4.5 Acceptable Use

#### 4.5.1 Permitted Activities

- Accessing corporate email and calendar via approved applications
- Using approved business applications within managed containers
- Accessing company intranet and collaboration tools (Microsoft 365, Teams)
- Storing work-related documents in approved cloud storage only
- Participating in company-approved communication platforms

#### 4.5.2 Prohibited Activities

- Storing INTERNAL or RESTRICTED data locally on personal devices
- Connecting to unsecured or public Wi-Fi networks without VPN
- Installing unauthorized applications from untrusted sources
- Sharing device access credentials with others
- Disabling or circumventing security controls
- Email auto-forwarding to personal accounts
- Copying company data to personal cloud services (iCloud, Google Drive personal accounts, Dropbox)
- Using personal devices in restricted areas where photography is prohibited
- Bypassing DLP controls

### 4.6 Authentication and Access Control

- Access to Microsoft 365 and other SaaS applications shall use Single Sign-On (SSO) with Multi-Factor Authentication (MFA)
- Microsoft 365 shall be the identity provider where supported
- Certificate-based authentication shall be used for VPN connections where technically feasible
- Session timeouts shall be enforced per application sensitivity

### 4.7 Network Security

- VPN must be used when accessing corporate resources from external networks
- Employees shall connect only to trusted, secured Wi-Fi networks
- Bluetooth pairing with unknown devices is prohibited when connected to corporate resources
- NFC should be disabled when not in use

### 4.8 Incident Reporting and Response

#### 4.8.1 Reportable Events

The following must be reported to IT Security immediately:

- Lost or stolen device
- Suspected malware infection
- Unauthorized access to corporate data
- Security control failures or bypasses
- Suspicious applications or activity

#### 4.8.2 Reporting Procedure

1. Contact IT Security Helpdesk immediately: security@gridsite.com or ext. 5555
2. Provide device details and incident description
3. Follow instructions for device isolation or remote wipe
4. Complete incident report within 24 hours

#### 4.8.3 Lost or Stolen Devices

- Lost or stolen devices must be reported immediately for access revocation and evidence capture
- Immediate remote lock will be initiated upon report
- Remote wipe will be executed if device is not recovered within 24 hours
- Full device wipe may be necessary based on risk assessment and data classification exposure

### 4.9 Termination and Offboarding

#### 4.9.1 Planned Departure

Upon resignation or planned departure:

1. Corporate data and applications will be removed from personal devices
2. MDM/MAM profile will be uninstalled
3. Access to corporate resources will be revoked
4. Employee must confirm data removal completion

#### 4.9.2 Involuntary Termination

In cases of involuntary termination:

- Immediate remote wipe of corporate data may be executed
- Device may be temporarily locked pending data removal
- Full device wipe may be required if separation of data is not possible

### 4.10 Privacy

#### 4.10.1 Company Rights

GridSite reserves the right to:

- Monitor enrolled devices for security compliance
- Access corporate data and applications on enrolled devices
- Remotely wipe corporate data and applications
- Perform full device wipe in cases of security incidents or policy violations

#### 4.10.2 Employee Privacy Protections

GridSite commits to:

- Separating personal and corporate data through containerization where technically feasible
- Not accessing personal applications, photos, or data outside of corporate containers
- Providing transparency about what data is collected and monitored
- Limiting device wipes to corporate containers when possible

#### 4.10.3 Data Collection and Logging

- Logging for communications and access is enabled where technically feasible
- Systems that cannot forward logs require periodic manual review and export
- The MDM/MAM solution collects: device type, model, OS version, security compliance status, installed corporate applications, and network connection information
- Device location is collected only when explicitly enabled for lost device recovery

### 4.11 Support Responsibilities

#### 4.11.1 IT Support Scope

IT Support will provide assistance for:

- MDM/MAM enrollment and configuration
- Corporate application installation and troubleshooting
- VPN and network connectivity issues
- Security incident response

#### 4.11.2 Employee Responsibilities

Employees are responsible for:

- Hardware maintenance, repairs, and replacement
- Operating system updates and upgrades
- Personal application support
- Carrier and service plan costs
- Data backup of personal information

## 5. Exceptions

Exceptions to this policy require ISMS Manager approval with documented compensating controls aligned to data classification. Exception requests must include:

- Business justification
- Risk assessment
- Proposed compensating controls
- Duration of exception
- Management approval

## 6. Compliance Measurement

Compliance with this policy is measured via:

- MDM/MAM enrollment and compliance reports
- DLP event monitoring and reporting
- Security incident records
- Quarterly security assessments of BYOD program
- Annual policy review and updates

## 7. Enforcement

Violations of this policy may result in:

- Temporary suspension of BYOD privileges
- Permanent revocation of BYOD privileges
- Disciplinary action up to and including termination
- Legal action in cases of willful misconduct or data breach

## 8. Related Documents

- [Data Classification and Handling Policy](./Data-Classification-and-Handling-Policy.md)
- [Endpoint Security Policy](./Endpoint-Security-Policy.md)
- [Remote Work Security Policy](./Remote-Work-Security-Policy.md)
- [Data Loss Prevention Standard](../standards/Data-Loss-Prevention-Standard.md)
- [Workstation Baseline](../standards/Workstation-Baseline.md)
- [Mobile Device Security Standard](../standards/Mobile-Device-Security-Standard.md)

## 9. Revision History

| Version | Date       | Author       | Description |
|---------|------------|--------------|-------------|
| 1.0.0   | 2025-11-05 |              | Initial BYOD policy with label-based access limits. |
| 1.1.0   | 2026-01-13 | Jake Neal    | Major expansion: Added detailed device requirements and minimum OS versions, BYOD eligibility and enrollment process, comprehensive acceptable use guidelines, data classification access matrix, authentication and network security requirements, incident reporting procedures, termination/offboarding procedures, privacy provisions with employee protections, support responsibility matrix, and enforcement provisions. Aligned with ISO 27001:2022 and ISO 27002:2022 requirements. |
