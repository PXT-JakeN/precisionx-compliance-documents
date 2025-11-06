---
title: "SOC 1 (ICFR) – Control Objectives Catalog (In-Scope Processes)"
doc_type: "Catalog"
id: "GRS-AUD-CAT-SOC1"
version: "1.1.0"
status: "Draft"
owner: "GRC Analyst"
program_manager: "Josh Mayorga, Compliance Manager"
approver: "Finance Controller"
approval_date: ""
effective_date: "2025-11-06"
next_review_date: ""
classification: "Internal – Controlled"
organization: "GridSite Technology LLC and its operating subsidiaries"
related_documents:
  - ../COORDINATION_REVIEW_PLAN.md
  - ../../plans/ICFR-Narrative-Billing-and-Revenue.md
---

## Document Control

| Field | Value |
|-------|-------|
| Title | SOC 1 (ICFR) – Control Objectives Catalog (In-Scope Processes) |
| Document ID | GRS-AUD-CAT-SOC1 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | GRC Analyst |
| Program Manager | Josh Mayorga, Compliance Manager |
| Approver | Finance Controller |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## Purpose

Reference list of ICFR-relevant control objectives for in-scope financial processes to support mapping.

## Objective List (Billing & Revenue – full)

| Standard | Objective ID | Title | Process | Brief Scope | Primary Documents | Supporting Documents | Evidence (examples) | Notes |
|----------|--------------|-------|---------|-------------|-------------------|----------------------|---------------------|-------|
| SOC 1 | ICFR-REV-01 | Completeness and accuracy of revenue recognition | Billing & Revenue | All billable activity is captured, rated, invoiced, and recorded accurately. | [P46](../../policies/Revenue-Recognition-and-Billing-Policy.md); [SD04](../../plans/ICFR-Narrative-Billing-and-Revenue.md) | [PR48](../../procedures/Revenue-and-Billing-Controls-Procedure.md); [R09](../../plans/Change-Log.md) | Invoices; source-to-bill trace; JE postings; reconciliations. |  |
| SOC 1 | ICFR-REV-02 | Segregation of duties in revenue processes | Billing & Revenue | Conflicting roles (create/approve/post) are segregated. | [P35](../../policies/Segregation-of-Duties-Policy.md); [P45](../../policies/Financial-Controls-Policy.md) | [P64](../../policies/Access-Control-Policy.md); [PR05](../../procedures/Privileged-Access-Elevation-Procedure.md) | SoD matrix; role assignments; approvals. |  |
| SOC 1 | ICFR-REV-03 | Access to financial systems | Billing & Revenue | Logical access provisioned/reviewed per least privilege. | [P64](../../policies/Access-Control-Policy.md); [PR49](../../procedures/Financial-System-Access-Procedure.md) | [P08](../../policies/Identity-and-Access-Management-Policy.md); [P09](../../policies/Authentication-and-MFA-Policy.md) | Access requests; periodic reviews; MFA logs. |  |
| SOC 1 | ICFR-REV-04 | Change management for financial systems | Billing & Revenue | Changes are authorized, tested, approved, and deployed. | [P19](../../policies/Change-and-Release-Management-Policy.md) | [PR07](../../procedures/Change-Control-Procedure.md); [PR09](../../procedures/Release-Management-Procedure.md) | Change tickets; approvals; UAT; rollback evidence. |  |
| SOC 1 | ICFR-REV-05 | Processing integrity of billing | Billing & Revenue | Rating, pricing, taxes, and billing runs are correct and complete. | [P46](../../policies/Revenue-Recognition-and-Billing-Policy.md) | [PR48](../../procedures/Revenue-and-Billing-Controls-Procedure.md) | Billing run logs; exception reports; tax tables. |  |
| SOC 1 | ICFR-REV-06 | Interface/data completeness (source→bill) | Billing & Revenue | Upstream usage/ordering data interfaces are complete. | [SD04](../../plans/ICFR-Narrative-Billing-and-Revenue.md) | [PR48](../../procedures/Revenue-and-Billing-Controls-Procedure.md); [R08](../../plans/Customer-Commitments-and-SLAs-Register.md) | Interface counts; control totals; error handling tickets. |  |
| SOC 1 | ICFR-REV-07 | Cut‑off | Billing & Revenue | Transactions are recorded in the correct accounting period. | [P45](../../policies/Financial-Controls-Policy.md) | [PR48](../../procedures/Revenue-and-Billing-Controls-Procedure.md) | Period-end checklists; cutoff reports. |  |
| SOC 1 | ICFR-REV-08 | Authorization of credits/adjustments | Billing & Revenue | Credits, write‑offs, and adjustments are approved. | [P46](../../policies/Revenue-Recognition-and-Billing-Policy.md) | [PR48](../../procedures/Revenue-and-Billing-Controls-Procedure.md) | Credit memos; approval workflow; limits. |  |
| SOC 1 | ICFR-REV-09 | Pricing and master data changes | Billing & Revenue | Price lists and master data are controlled and approved. | [P19](../../policies/Change-and-Release-Management-Policy.md) | [PR07](../../procedures/Change-Control-Procedure.md); [R02](../../plans/Asset-Inventory-and-CMDB.md) | Change tickets; approvals; audit logs. |  |
| SOC 1 | ICFR-REV-10 | Exception and dispute management | Billing & Revenue | Exceptions and disputes are tracked and resolved timely. | [P45](../../policies/Financial-Controls-Policy.md) | [PR50](../../procedures/Reconciliations-and-Exception-Management-Procedure.md); [PR29](../../procedures/Support-and-Escalation-Procedure.md) | Exception queue; SLAs; resolutions. |  |
| SOC 1 | ICFR-REV-11 | Reconciliations (subledger→GL) | Billing & Revenue | Regular reconciliations to GL with review and follow‑up. | [P45](../../policies/Financial-Controls-Policy.md) | [PR50](../../procedures/Reconciliations-and-Exception-Management-Procedure.md) | Reconciliation packs; reviewer sign‑offs. |  |
| SOC 1 | ICFR-REV-12 | Journal entry controls | Billing & Revenue | JEs are supported and reviewed/approved. | [P45](../../policies/Financial-Controls-Policy.md) |  | JE forms; approvals; narratives. |  |
| SOC 1 | ICFR-REV-13 | Subservice/vendor monitoring (ICFR) | Billing & Revenue | ICFR‑relevant vendors monitored; gaps mitigated. | [P27](../../policies/Subservice-Organization-Oversight-Policy.md) | [PR31](../../procedures/Subservice-Monitoring-Procedure.md) | SOC reports; bridge letters; gap plans. |  |
| SOC 1 | ICFR-REV-14 | Backup and recovery (financial systems) | Billing & Revenue | Backups and DR ensure availability/integrity. | [P25](../../policies/Backup-and-Restore-Policy.md) | [S08](../../standards/Backup-and-Immutability-Standard.md); [PR21](../../procedures/Backup-and-Restore-Procedure.md) | Backup jobs; restore tests; immutability configs. |  |
| SOC 1 | ICFR-REV-15 | Logging and audit trails | Billing & Revenue | Transaction and admin activity are logged and retained. | [P21](../../policies/Logging-Monitoring-and-SIEM-Policy.md) | [S07](../../standards/Logging-and-Time-Sync-Standard.md); [PR19](../../procedures/Logging-and-SIEM-Onboarding-Procedure.md) | Audit logs; retention; reviews. |  |
| SOC 1 | ICFR-REV-16 | Management review controls | Billing & Revenue | KPIs/variances reviewed; actions documented. | [P60](../../policies/Metrics-and-Continuous-Improvement-Policy.md) | [PR46](../../procedures/Management-Review-Procedure.md); [PL09](../../plans/Audit-and-Assessment-Plan.md) | MRC decks; minutes; follow‑ups. |  |
| SOC 1 | ICFR-REV-17 | Record retention | Billing & Revenue | Financial records retained per policy/regulation. | [P32](../../policies/Records-Management-and-Evidence-Policy.md) | [P30](../../policies/Data-Retention-and-Disposal-Policy.md) | Retention schedule; disposition logs. |  |
| SOC 1 | ICFR-REV-18 | Incident response (ICFR impact) | Billing & Revenue | Incidents affecting ICFR are triaged and disclosed. | [P22](../../policies/Incident-Response-Policy.md) | [PR13](../../procedures/IR-Runbook-General.md); [R10](../../plans/Incident-Log.md) | Incident timelines; PIRs. |  |
| SOC 1 | ICFR-REV-19 | Capacity/availability of billing platform | Billing & Revenue | Capacity and availability support timely revenue. | [P44](../../policies/Capacity-and-Performance-Management-Policy.md) | [R18](../../plans/Capacity-and-Availability-Reports.md) | Uptime; capacity trend; SLOs. |  |
| SOC 1 | ICFR-REV-20 | Confidentiality of customer billing data | Billing & Revenue | Sensitive billing data protected (supports integrity). | [P31](../../policies/Privacy-and-Data-Protection-Policy.md) | [S24](../../standards/Data-Loss-Prevention-Standard.md); [P16](../../policies/Cryptography-and-Key-Management-Policy.md) | Encryption configs; DLP alerts. |  |

## Document-to-Objectives Mapping (Billing & Revenue)

| Document | Doc ID | Type | Objectives (Primary) | Objectives (Supporting) |
|----------|--------|------|-----------------------|-------------------------|
| Revenue Recognition & Billing Policy | P46 | Policy | ICFR-REV-01, ICFR-REV-05, ICFR-REV-08 | ICFR-REV-06 |
| ICFR Narrative – Billing & Revenue | SD04 | Narrative | ICFR-REV-01, ICFR-REV-06 | ICFR-REV-02, ICFR-REV-04, ICFR-REV-05, ICFR-REV-07 |
| Revenue & Billing Controls Procedure | PR48 | Procedure | ICFR-REV-10, ICFR-REV-11 | ICFR-REV-01, ICFR-REV-05, ICFR-REV-06, ICFR-REV-07, ICFR-REV-08 |
| Segregation of Duties Policy | P35 | Policy | ICFR-REV-02 |  |
| Financial Controls Policy | P45 | Policy | ICFR-REV-02, ICFR-REV-07, ICFR-REV-11, ICFR-REV-12 | ICFR-REV-16 |
| Access Control Policy | P64 | Policy | ICFR-REV-03 | ICFR-REV-02 |
| Financial System Access Procedure | PR49 | Procedure | ICFR-REV-03 |  |
| Change & Release Mgmt Policy | P19 | Policy | ICFR-REV-04, ICFR-REV-09 | ICFR-REV-19 |
| Change Control Procedure | PR07 | Procedure |  | ICFR-REV-04, ICFR-REV-09 |
| Release Management Procedure | PR09 | Procedure |  | ICFR-REV-04, ICFR-REV-19 |
| Reconciliations & Exception Mgmt Procedure | PR50 | Procedure | ICFR-REV-10, ICFR-REV-11 |  |
| Support & Escalation Procedure | PR29 | Procedure |  | ICFR-REV-10 |
| Backup & Restore Policy | P25 | Policy | ICFR-REV-14 |  |
| Backup & Immutability Standard | S08 | Standard |  | ICFR-REV-14 |
| Backup & Restore Procedure | PR21 | Procedure |  | ICFR-REV-14 |
| Logging, Monitoring & SIEM Policy | P21 | Policy | ICFR-REV-15 |  |
| Logging & Time Sync Standard | S07 | Standard |  | ICFR-REV-15 |
| SIEM Onboarding Procedure | PR19 | Procedure |  | ICFR-REV-15 |
| Metrics & Continuous Improvement Policy | P60 | Policy | ICFR-REV-16 |  |
| Management Review Procedure | PR46 | Procedure |  | ICFR-REV-16 |
| Audit & Assessment Plan | PL09 | Plan |  | ICFR-REV-16 |
| Records Mgmt & Evidence Policy | P32 | Policy | ICFR-REV-17 | ICFR-REV-01 |
| Data Retention & Disposal Policy | P30 | Policy |  | ICFR-REV-17 |
| Incident Response Policy | P22 | Policy | ICFR-REV-18 |  |
| IR Runbook – General | PR13 | Procedure |  | ICFR-REV-18 |
| Incident Log | R10 | Register |  | ICFR-REV-18 |
| Capacity & Performance Mgmt Policy | P44 | Policy | ICFR-REV-19 |  |
| Capacity & Availability Reports | R18 | Register |  | ICFR-REV-19 |
| Privacy & Data Protection Policy | P31 | Policy | ICFR-REV-20 |  |
| Data Loss Prevention Standard | S24 | Standard |  | ICFR-REV-20 |
| Cryptography & Key Mgmt Policy | P16 | Policy |  | ICFR-REV-20 |
| Subservice Org Oversight Policy | P27 | Policy | ICFR-REV-13 |  |
| Subservice Monitoring Procedure | PR31 | Procedure |  | ICFR-REV-13 |
| Change Log | R09 | Register |  | ICFR-REV-01, ICFR-REV-04, ICFR-REV-09 |
| Customer Commitments & SLAs Register | R08 | Register |  | ICFR-REV-06 |

## Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Seeded ICFR objectives catalog. |
| 1.1.0   | 2025-11-06 |        | Added full Billing & Revenue objective list with Primary/Supporting/Evidence columns. |


