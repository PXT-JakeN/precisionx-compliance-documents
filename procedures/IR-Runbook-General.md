---
title: "Incident Response Runbook – General"
doc_type: "Procedure"
id: "GRS-ISMS-PRC-013"
version: "1.0.1"
status: "Draft"
owner: "Security Operations Lead"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
related_documents:
  - ../policies/Incident-Response-Policy.md
  - ../policies/Logging-Monitoring-and-SIEM-Policy.md
  - ../plans/Crisis-Communications-Plan.md
  - ../plans/Incident-Playbooks.md
  - ../plans/Incident-Log.md
references:
  - ISO/IEC 27035 Incident Management
  - AICPA SOC 2 TSC (CC7)
iso_clauses: ["8"]
soc2_criteria: ["CC7"]
bcms_clauses: []
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Incident Response Runbook – General |
| Document ID | GRS-ISMS-PRC-013 |
| Version | 1.0.1 |
| Status | Draft |
| Owner | Security Operations Lead |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Provide step-by-step guidance for responding to security incidents across common scenarios, ensuring
consistent actions, record-keeping, and communication.

## 2. Scope

Applies to all incidents declared per the Incident Response Policy.

## 3. Prerequisites

- On-call roster and paging configured
- Access to SIEM, EDR, cloud consoles, ticketing, and comms tools
- Current asset inventory and network/data flow diagrams

## 4. Severity Matrix (Example)

| Severity | Criteria (example) | Target MTTD | Target MTTR | Notification |
|---------|---------------------|-------------|-------------|-------------|
| SEV1 | Widespread outage or confirmed data breach | < 15 min | < 24 hrs | Exec, Legal, Customers/Regulators |
| SEV2 | Significant impact; potential data exposure | < 30 min | < 72 hrs | Exec, Legal |
| SEV3 | Limited impact; contained | < 2 hr | < 7 days | Mgmt |
| SEV4 | Low impact; informational | Best effort | Best effort | As needed |

## 5. Procedure

1) Preparation
   - Confirm on-call resources; verify tooling health; review recent PIR action items.

2) Detection and Triage
   - Validate alert fidelity; correlate events; determine scope. Classify severity; declare incident and open case.

3) Containment
   - Short-term: isolate hosts/accounts; block indicators; apply WAF/ACL rules. Evaluate customer impact.
   - Long-term: deploy patches/config changes; roll keys; increase logging.

4) Eradication
   - Remove malware/artifacts; rotate credentials; close exploited vectors; validate with scans.

5) Recovery
   - Restore services; monitor for recurrence; validate integrity; communicate restoration status.

6) Post-Incident Review
   - Within 10 business days, conduct PIR: timeline, root cause, contributing factors, CAPA with owners/dates.
   - Update risk register and SoA if control gaps identified.

## 6. Evidence and Records

- Preserve logs, images, and exports with chain-of-custody; document actions and approvals in the case record.
- Update the Incident Log and attach PIR outcomes.

## 7. Roles and RACI (Summary)

| Activity | IC | SecOps | SecEng | Legal/Privacy | Comms | Owner |
|----------|----|--------|--------|---------------|-------|-------|
| Declare incident | R | A | C | C | C | SecOps Lead |
| Containment | A | R | R | C | C | IC |
| Evidence handling | A | R | C | C | I | Forensics Lead |
| Communications | C | C | I | A | R | Comms Lead |
| PIR/CAPA | A | R | C | C | C | Compliance Mgr |

## 8. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.1   | 2025-11-05 |        | Added Document Control section; standardized header format. |
| 1.0.0   | 2025-11-05 |        | Initial general IR runbook with lifecycle and roles. |


