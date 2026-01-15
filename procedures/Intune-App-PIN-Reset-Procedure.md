---
title: "Intune App PIN Reset Procedure"
doc_type: "Procedure"
id: "GRS-ISMS-PRC-027"
version: "1.0.0"
status: "Draft"
owner: "IT Operations Lead"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ../policies/Mobile-Device-and-BYOD-Policy.md
  - ../policies/Endpoint-Security-Policy.md
  - ../policies/Identity-and-Access-Management-Policy.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Intune App PIN Reset Procedure |
| Document ID | GRS-ISMS-PRC-027 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | IT Operations Lead |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define the steps for resetting a user's Microsoft Intune App Protection Policy PIN when a user has forgotten their PIN or requires a PIN reset for security reasons. This procedure applies to managed Microsoft 365 applications (Outlook, Teams, Word, Excel, PowerPoint, SharePoint) on personal iOS and Android devices.

## 2. Scope

This procedure applies to:

- All BYOD users with Intune App Protection Policies applied
- iOS and Android personal devices accessing managed Microsoft 365 applications
- IT Support staff responsible for processing PIN reset requests

## 3. Roles

| Role | Responsibility |
|------|----------------|
| End User | Submits PIN reset request via support ticket |
| IT Support | Verifies user identity, performs selective wipe, documents action |
| IT Operations Lead | Approves PIN resets in escalated or suspicious cases |

## 4. Prerequisites

- Access to Microsoft Intune Admin Center (https://intune.microsoft.com)
- Appropriate Intune administrator role (Intune Administrator, Help Desk Operator, or equivalent)
- User identity verification method established

## 5. Procedure

### 5.1 User Request Submission

1. User submits a support ticket to support@precisionx.tech requesting an app PIN reset
2. User must provide:
   - Full name
   - Work email address
   - Device type (iOS or Android)
   - Reason for PIN reset (forgot PIN, security concern, etc.)

### 5.2 Identity Verification

Before performing any PIN reset, IT Support must verify the user's identity:

1. Confirm the request originated from the user's corporate email address, OR
2. Call the user back on their registered phone number to verify, OR
3. Verify identity via Microsoft Teams video call with a known manager

**Do not perform a PIN reset without identity verification.**

### 5.3 Perform Selective App Wipe (Intune Admin Center)

The only method to reset an Intune App Protection Policy PIN is to perform a selective wipe of managed app data. This removes corporate data from managed apps and forces the user to set a new PIN upon reopening.

**Steps:**

1. Sign in to the **Microsoft Intune Admin Center** at https://intune.microsoft.com

2. Navigate to **Apps** → **Monitor** → **App protection status**

3. Click **User status** and search for the user by name or email

4. Click on the user's name to view their protected apps and devices

5. Locate the device requiring the PIN reset

6. Click on the device, then select **Wipe**
   - This performs a **selective wipe** (managed app data only)
   - Personal data, photos, and personal apps are NOT affected

7. Confirm the wipe action when prompted

8. Document the action in the support ticket:
   - Date and time of wipe
   - Device identifier
   - IT staff member who performed the action
   - Ticket number

### 5.4 Alternative Method: Wipe via User Profile

1. Sign in to the **Microsoft Intune Admin Center** at https://intune.microsoft.com

2. Navigate to **Users** → **All users**

3. Search for and select the user

4. Click **Managed apps** in the left menu

5. Select the device to wipe

6. Click **Wipe** to remove managed app data

7. Document the action in the support ticket

### 5.5 User Re-enrollment

After the selective wipe, instruct the user:

1. Open any managed Microsoft 365 app (Outlook, Teams, etc.)

2. Sign in with their work account when prompted

3. **Android users only**: Ensure Microsoft Intune Company Portal is installed and signed in

4. When prompted, create a new 6-digit PIN

5. Confirm the new PIN

6. The app will sync and restore access to corporate data

**Note:** The user will need to re-enter their new PIN in each managed app the first time they open it after the wipe.

## 6. Important Considerations

### 6.1 What Selective Wipe Removes

| Removed | Not Removed |
|---------|-------------|
| Corporate email and calendar data | Personal emails and apps |
| Corporate files in managed apps | Personal photos and files |
| Cached Teams chats and data | Device settings |
| SharePoint/OneDrive work files | Personal cloud storage |
| App Protection Policy PIN | Device passcode |

### 6.2 Data Recovery

- Email will re-sync from Exchange Online after sign-in
- Teams chats and channels will reload from the cloud
- OneDrive/SharePoint files remain in the cloud and will be accessible after sign-in
- Any locally cached data that was not synced will be lost

### 6.3 Security Considerations

- Multiple PIN reset requests from the same user may indicate a security issue
- If a user reports suspicious activity alongside a PIN reset request, escalate to IT Security
- Consider requiring a password reset if PIN compromise is suspected

## 7. Records & Evidence

For each PIN reset, document and retain:

- Support ticket number
- User name and email
- Date and time of request
- Identity verification method used
- Date and time of selective wipe
- IT staff member who performed the action
- User confirmation of successful re-enrollment

## 8. Metrics

| Metric | Target |
|--------|--------|
| PIN reset completion time | Within 4 business hours of verified request |
| Identity verification compliance | 100% of requests verified before action |
| Documentation compliance | 100% of actions documented in tickets |

## 9. Revision History

| Version | Date       | Author    | Description |
|---------|------------|-----------|-------------|
| 1.0.0   | 2026-01-13 | Jake Neal | Initial procedure for Intune App Protection Policy PIN resets via selective wipe. |

