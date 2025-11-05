---
title: "DCIM/Telemetry Standard"
doc_type: "Standard"
id: "GRS-ISMS-STD-016"
version: "1.0.0"
status: "Draft"
owner: "Facilities Lead"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
related_documents:
  - ../standards/NOC-Build-Standard.md
  - ../policies/Logging-Monitoring-and-SIEM-Policy.md
references:
  - ISO/IEC 27002:2022 (physical and environmental)
---

## Document Control

| Field | Value |
|-------|-------|
| Title | DCIM/Telemetry Standard |
| Document ID | GRS-ISMS-STD-016 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Facilities Lead |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define telemetry requirements for environmental, power, and infrastructure monitoring at NOC and GridColo
sites to support availability and incident response.

## 2. Scope

Sensors and DCIM platforms capturing temperature, humidity, power draw, UPS/generator status, and rack
conditions at managed sites.

## 3. Control Requirements

| Req ID | Requirement | Implementation | Evidence |
|--------|-------------|----------------|----------|
| DCIM-01 | Sensor coverage | Temperature, humidity, airflow, leak, door, and power sensors deployed | Sensor inventory |
| DCIM-02 | Polling & thresholds | Poll at defined intervals; set thresholds and alerting for anomalies | DCIM configs; alert logs |
| DCIM-03 | Time sync | Synchronize DCIM systems to approved NTP sources | NTP settings |
| DCIM-04 | Logging | Forward events to SIEM when supported; manual exports otherwise | SIEM dashboards; exports |
| DCIM-05 | Data retention | Retain telemetry for capacity and trend analysis per policy | Retention policies |
| DCIM-06 | Testing | Quarterly sensor/alert tests with documented results | Test records |

## 4. Roles and Responsibilities

Facilities configures and maintains sensors; SecOps integrates alerting and reviews trends; NOC acts on alarms
and coordinates incident response.

## 5. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial DCIM/telemetry standard. |


