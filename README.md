<div align="center">

# Ranas Mukminov · Run_as_daemon

**Security engineering · DevSecOps · Linux & Kubernetes hardening**

Building and reviewing practical security tooling for cloud-native infrastructure.
My focus is on reproducible findings, safer defaults, and actionable remediation.

[Website](https://run-as-daemon.dev) · [Projects](https://github.com/ranas-mukminov?tab=repositories) · [LinkedIn](https://www.linkedin.com/in/ranas-mukminov/) · [Telegram](https://t.me/en_run_as_daemon_dev)

</div>

---

## Technical focus

- **Infrastructure security:** Linux hardening, SSH, network segmentation, IAM, secrets management, secure backups.
- **Cloud-native security:** Kubernetes / K3s, RBAC, workload security contexts, policy-as-code, GitOps, CI security gates.
- **Detection & response:** telemetry, incident timelines, audit evidence, remediation and recovery exercises.
- **Responsible research:** scoped, documented and authorized assessments; controlled validation and reporting.

My infrastructure laboratory includes a multi-node K3s environment spanning VPS and other Linux hosts. Detailed production/client configurations are intentionally not public; repository examples use sample data.

## Selected open-source work

| Project | What you can inspect |
| --- | --- |
| [Kube-Simple-Audit](https://github.com/ranas-mukminov/Kube-Simple-Audit) | Small Bash-based Kubernetes configuration check for privileged workloads, root execution settings, missing resource limits and default-namespace workloads. |
| [Secure-K3s-GitOps-Template](https://github.com/ranas-mukminov/Secure-K3s-GitOps-Template) | Reference template, infrastructure and Kubernetes manifests for a secure-by-default K3s deployment; review configuration for your environment before use. |
| [AutoHarden-Toolkit](https://github.com/ranas-mukminov/AutoHarden-Toolkit) | Linux hardening CLI with a dry-run default, opt-in apply mode and sample reports. |
| [Linux Hardening Blueprint](https://github.com/ranas-mukminov/linux-hardening-blueprint-small-business) | Ansible and CLI implementation of configurable Linux baselines; see repository CI for current validation status. |
| [Incident Timeline Extractor](https://github.com/ranas-mukminov/incident-timeline-extractor) | Structured incident timeline extraction from operational logs, with tests and documented usage. |
| [Secure Backups + Drill Lab](https://github.com/ranas-mukminov/secure-backups-drill-lab) | Backup orchestration and recovery drill exercises, including tests and GitHub Actions workflows. |
| [KubeGuardian Core](https://github.com/ranas-mukminov/KubeGuardian-Core) | Architecture and showcase code for Kubernetes runtime security; not a complete production runtime engine. |

## Contributions beyond my repositories

These are public review records, not claims of private certifications or awards:

- **[Powerpipe #1145 — merged](https://github.com/turbot/powerpipe/pull/1145):** prevent an ECharts snapshot failure when a chart instance has been disposed (merged October 27, 2026).
- **[Kyverno policies #1583 — open](https://github.com/kyverno/policies/pull/1583):** extend Secret-from-environment policy coverage to init and ephemeral containers.
- **[Kyverno policies #1567 — open](https://github.com/kyverno/policies/pull/1567):** extend image-tag validation to init and ephemeral containers.

Open PRs are work under review, **not merged upstream changes**. The linked discussions and diffs show the exact contributions.

## How I approach authorized security testing

1. Confirm asset ownership, explicit written authorization, defined source IPs, timing, methods and stop conditions.
2. Prefer isolated test environments and synthetic data; do not collect or publish customer data.
3. Reproduce a suspected issue with the **least intrusive** practical evidence.
4. Report the affected component, impact, evidence, reproduction in the approved scope and remediation.
5. Verify the fix and preserve an audit trail. Share real engagement details only with the client's consent.

For confidential engagements I can supply appropriately redacted evidence only when permitted by the relevant agreement. This profile is **not** a claim of privileged cyber-model access or any security certification.

## Architecture & services

**Core stack:** Rocky Linux · Kubernetes / K3s · Helm · Terraform / OpenTofu · Ansible · Python · Bash · Traefik · WireGuard / AmneziaWG · Prometheus · Grafana · Zabbix.

I work on infrastructure architecture reviews, hardening baselines, automation, operational monitoring and scoped security reviews. For commercial engagements, use the contact links above to discuss an appropriate statement of work.

**Other projects:** [152Guard](https://152guard.space) · [FTOPS](https://ftops.space) · [Run_as_daemon HQ](https://run-as-daemon.pro)

---

<sub>Some repositories are reference implementations or prototypes. Read each project's documented status and limitations before deployment. No production credentials, customer targets or confidential engagement materials are published here.</sub>
