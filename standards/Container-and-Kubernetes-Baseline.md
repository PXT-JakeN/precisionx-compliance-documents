---
title: "Container and Kubernetes Baseline"
doc_type: "Standard"
id: "GRS-ISMS-STD-003"
version: "1.0.0"
status: "Draft"
owner: "Security Engineering Lead"
approver: "Executive Management, GridSite Technology LLC"
approval_date: ""
effective_date: ""
next_review_date: ""
related_documents:
  - ../standards/CI-CD-Security-Standard.md
  - ../standards/Secrets-Management-Standard.md
  - ../standards/Logging-and-Time-Sync-Standard.md
  - ../policies/Logging-Monitoring-and-SIEM-Policy.md
references:
  - CIS Kubernetes Benchmark
  - OWASP Kubernetes Top 10
---

## Document Control

| Field | Value |
|-------|-------|
| Title | Container and Kubernetes Baseline |
| Document ID | GRS-ISMS-STD-003 |
| Version | 1.0.0 |
| Status | Draft |
| Owner | Security Engineering Lead |
| Approver | Executive Management, GridSite Technology LLC |
| Approval Date |  |
| Effective Date |  |
| Next Review Date |  |

## 1. Purpose

Define baseline controls for container images, registries, clusters, and workloads to reduce risk and ensure
consistent, auditable deployments.

## 2. Scope

All container images and Kubernetes clusters used by GridSite services.

## 3. Control Requirements

| Req ID | Requirement | Implementation | Evidence |
|--------|-------------|----------------|----------|
| K8S-01 | Image sources | Use trusted base images; pin digests; avoid :latest | Dockerfiles; registry policies |
| K8S-02 | Image signing | Sign images and verify at admission; enforce policy | Sigstore/notation configs |
| K8S-03 | Vulnerability scanning | Scan images on build and in registry; block criticals | Scanner reports |
| K8S-04 | Least privilege | Run as non‑root; drop capabilities; read‑only FS; resource limits | PodSecurity/PSA; manifests |
| K8S-05 | Network policies | Apply default‑deny; explicit egress/ingress network policies | NetworkPolicy manifests |
| K8S-06 | Secrets | Mount via runtime from vault; never bake into images | Vault injector configs |
| K8S-07 | Admission control | Enforce policies (Pod Security Admission/OPA/Gatekeeper/Kyverno) | Policy sets; audit logs |
| K8S-08 | Logging & time | Forward control plane and workload logs where supported; manual review if not | Log configs; reviews |
| K8S-09 | RBAC | Namespace isolation; least‑privilege service accounts; no default tokens | RBAC manifests |
| K8S-10 | Backup/DR | Backup etcd and critical state; document restore procedures | Backup dashboards; runbooks |

## 4. Roles and Responsibilities

Security Engineering defines policies and admission controls; Platform/DevOps implements cluster configs;
SecOps monitors logs and findings.

## 5. Revision History

| Version | Date       | Author | Description |
|---------|------------|--------|-------------|
| 1.0.0   | 2025-11-05 |        | Initial container and Kubernetes baseline. |


