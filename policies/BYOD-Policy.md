# PrecisionX BYOD Policy

**Document ID:** POL-SEC-008  
**Version:** 2.0  
**Effective Date:** January 13, 2026  
**Last Reviewed:** January 13, 2026  
**Owner:** Information Security Department  
**Classification:** Internal Use Only

---

## 1. Purpose

This Bring Your Own Device (BYOD) Policy establishes the requirements and responsibilities for employees who use personally-owned devices to access PrecisionX corporate resources, networks, and data. The policy aims to balance employee flexibility with the protection of company information assets.

## 2. Scope

This policy applies to:
- All PrecisionX employees, contractors, and third-party personnel
- All personally-owned devices used to access company resources, including:
  - Smartphones and tablets
  - Laptops and desktop computers
  - Wearable devices with network connectivity
  - Any other personal devices connecting to corporate systems

## 3. Policy Statement

PrecisionX permits the use of personal devices for work purposes provided that employees comply with the security requirements outlined in this policy. The use of personal devices is a privilege, not a right, and may be revoked at any time.

## 4. Eligibility and Enrollment

### 4.1 Eligibility Requirements
- Employee must be in good standing with the company
- Role must be approved for BYOD participation by department manager
- Employee must complete BYOD security awareness training
- Device must meet minimum security specifications (Section 5)

### 4.2 Enrollment Process
1. Submit BYOD enrollment request through the IT Service Portal
2. Review and sign the BYOD User Agreement
3. Schedule device configuration appointment with IT Support
4. Complete Mobile Device Management (MDM) enrollment
5. Receive confirmation of successful enrollment

## 5. Device Requirements

### 5.1 Minimum Specifications
| Device Type | Operating System | Minimum Version |
|-------------|------------------|-----------------|
| iOS Devices | iOS | 16.0 or later |
| Android Devices | Android | 13.0 or later |
| Windows Laptops | Windows | Windows 11 |
| macOS Devices | macOS | Ventura (13.0) or later |

### 5.2 Security Requirements
All enrolled devices must have:
- [ ] Device encryption enabled
- [ ] Screen lock with PIN/password (minimum 6 characters) or biometric authentication
- [ ] Automatic screen lock after 2 minutes of inactivity
- [ ] Up-to-date operating system with latest security patches
- [ ] Company-approved MDM solution installed and active
- [ ] Company-approved antivirus/anti-malware software (where applicable)
- [ ] Remote wipe capability enabled
- [ ] No jailbreaking, rooting, or unauthorized modifications

## 6. Acceptable Use

### 6.1 Permitted Activities
- Accessing corporate email and calendar
- Using approved business applications
- Accessing company intranet and collaboration tools
- Storing work-related documents in approved cloud storage
- Participating in company-approved communication platforms

### 6.2 Prohibited Activities
- Storing highly confidential or regulated data locally on personal devices
- Connecting to unsecured or public Wi-Fi networks without VPN
- Installing unauthorized applications from untrusted sources
- Sharing device access credentials with others
- Using the device while it is connected to untrusted computers
- Disabling or circumventing security controls
- Using personal devices in restricted areas where photography is prohibited

## 7. Security Controls

### 7.1 Mobile Device Management (MDM)
Enrolled devices must maintain active MDM enrollment, which enables:
- Configuration profile management
- Application inventory and management
- Security compliance monitoring
- Remote lock and wipe capabilities
- Certificate-based authentication

### 7.2 Data Protection
- All corporate data must be stored within approved, containerized applications
- Data at rest must be encrypted
- Data in transit must use TLS 1.2 or higher
- Automatic backup of corporate data to approved cloud services only
- No synchronization of corporate data to personal cloud accounts

### 7.3 Network Security
- VPN must be used when accessing corporate resources from external networks
- Employees must connect only to trusted, secured Wi-Fi networks
- Bluetooth pairing with unknown devices is prohibited
- NFC should be disabled when not in use

## 8. Privacy

### 8.1 Company Rights
PrecisionX reserves the right to:
- Monitor enrolled devices for security compliance
- Access corporate data and applications on enrolled devices
- Remotely wipe corporate data and applications
- Perform full device wipe in cases of security incidents or policy violations

### 8.2 Employee Privacy
PrecisionX commits to:
- Separating personal and corporate data through containerization
- Not accessing personal applications, photos, or data
- Providing transparency about what data is collected and monitored
- Limiting device wipes to corporate containers when possible

### 8.3 Data Collection
The MDM solution collects the following information:
- Device type, model, and operating system version
- Security compliance status
- Installed corporate applications
- Device location (only when explicitly enabled for lost device recovery)
- Network connection information

## 9. Support and Maintenance

### 9.1 IT Support Scope
IT Support will provide assistance for:
- MDM enrollment and configuration
- Corporate application installation and troubleshooting
- VPN and network connectivity issues
- Security incident response

### 9.2 Employee Responsibilities
Employees are responsible for:
- Hardware maintenance and repairs
- Operating system updates and upgrades
- Personal application support
- Carrier and service plan costs
- Data backup of personal information

## 10. Incident Reporting

### 10.1 Reportable Events
The following must be reported to IT Security immediately:
- Lost or stolen device
- Suspected malware infection
- Unauthorized access to corporate data
- Security control failures or bypasses
- Suspicious applications or activity

### 10.2 Reporting Procedure
1. Contact IT Security Helpdesk: security@precisionx.com or ext. 5555
2. Provide device details and incident description
3. Follow instructions for device isolation or wipe
4. Complete incident report within 24 hours

## 11. Termination and Offboarding

### 11.1 Voluntary Departure
Upon resignation or planned departure:
1. Corporate data and applications will be removed from personal devices
2. MDM profile will be uninstalled
3. Access to corporate resources will be revoked
4. Employee must confirm data removal completion

### 11.2 Involuntary Termination
In cases of involuntary termination:
- Immediate remote wipe of corporate data may be executed
- Device may be temporarily locked pending data removal
- Full device wipe may be required if separation of data is not possible

### 11.3 Lost or Stolen Devices
- Immediate remote lock will be initiated
- Remote wipe will be executed if device is not recovered within 24 hours
- Full device wipe may be necessary based on risk assessment

## 12. Compliance and Enforcement

### 12.1 Monitoring
IT Security will conduct:
- Continuous automated compliance monitoring via MDM
- Quarterly security assessments of BYOD program
- Annual policy review and updates

### 12.2 Non-Compliance
Violations of this policy may result in:
- Temporary suspension of BYOD privileges
- Permanent revocation of BYOD privileges
- Disciplinary action up to and including termination
- Legal action in cases of willful misconduct

## 13. Reimbursement

PrecisionX provides the following BYOD allowances (subject to approval):
| Role Level | Monthly Allowance |
|------------|-------------------|
| Individual Contributor | $50 |
| Manager | $75 |
| Director and Above | $100 |

Reimbursement is processed through the standard expense system and requires enrollment in the BYOD program.

## 14. Related Documents

- POL-SEC-001: Information Security Policy
- POL-SEC-003: Acceptable Use Policy
- POL-SEC-005: Data Classification Policy
- POL-SEC-012: Remote Work Security Policy
- STD-SEC-002: Mobile Device Security Standard
- PRC-SEC-008: BYOD Enrollment Procedure

## 15. Definitions

| Term | Definition |
|------|------------|
| BYOD | Bring Your Own Device - the practice of using personal devices for work purposes |
| MDM | Mobile Device Management - software for securing and managing mobile devices |
| Containerization | Technology that separates corporate and personal data on a device |
| Remote Wipe | The ability to erase data from a device remotely |
| Jailbreaking/Rooting | Removing manufacturer restrictions from a device |

## 16. Revision History

| Version | Date | Author | Description |
|---------|------|--------|-------------|
| 1.0 | March 15, 2024 | IT Security Team | Initial policy release |
| 1.1 | September 1, 2024 | IT Security Team | Updated OS version requirements |
| 2.0 | January 13, 2026 | IT Security Team | Major revision: Updated device requirements, added reimbursement section, enhanced privacy provisions |

---

## Approval

| Role | Name | Signature | Date |
|------|------|-----------|------|
| Chief Information Security Officer | _______________ | _______________ | _______________ |
| Chief Information Officer | _______________ | _______________ | _______________ |
| VP Human Resources | _______________ | _______________ | _______________ |
| Legal Counsel | _______________ | _______________ | _______________ |

---

*For questions regarding this policy, contact the Information Security Department at security@precisionx.com*

