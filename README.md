<div align="center">

# Run_as_daemon
### Security Architect · DevSecOps · FinTech Zero-Trust

**I design infrastructure that secures itself — without slowing your delivery.**  
K3s · GitOps · Zero-Trust · Cilium · Vault · WireGuard

<br/>

[![Website](https://img.shields.io/badge/run--as--daemon.dev-0A0A0A?style=for-the-badge&logo=googlechrome&logoColor=00E5A8)](https://run-as-daemon.dev)
[![HQ](https://img.shields.io/badge/run--as--daemon.pro-0A0A0A?style=for-the-badge&logo=vercel&logoColor=00E5A8)](https://run-as-daemon.pro)
[![FTOPS](https://img.shields.io/badge/ftops.space-0A0A0A?style=for-the-badge&logo=wireguard&logoColor=00E5A8)](https://ftops.space)
[![152Guard](https://img.shields.io/badge/152guard.space-0A0A0A?style=for-the-badge&logo=shield&logoColor=00E5A8)](https://152guard.space)

<br/>

[![Telegram](https://img.shields.io/badge/Telegram-0A0A0A?style=flat-square&logo=telegram&logoColor=26A5E4)](https://t.me/en_run_as_daemon_dev)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A0A0A?style=flat-square&logo=linkedin&logoColor=0A66C2)](https://www.linkedin.com/in/ranas-mukminov/)
[![X](https://img.shields.io/badge/X-0A0A0A?style=flat-square&logo=x&logoColor=white)](https://x.com/mukminov_ranas)

</div>

---

<div align="center">

### Stack

![K3s](https://img.shields.io/badge/K3s-FFC61C?style=flat-square&logo=kubernetes&logoColor=black)
![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white)
![Cilium](https://img.shields.io/badge/Cilium-F8C519?style=flat-square&logo=cilium&logoColor=black)
![Vault](https://img.shields.io/badge/Vault-000000?style=flat-square&logo=vault&logoColor=yellow)
![WireGuard](https://img.shields.io/badge/WireGuard-88171A?style=flat-square&logo=wireguard&logoColor=white)
![Ansible](https://img.shields.io/badge/Ansible-EE0000?style=flat-square&logo=ansible&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![GitOps](https://img.shields.io/badge/GitOps-3D7EED?style=flat-square&logo=git&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Helm](https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white)

<br/>

<img src="https://skillicons.dev/icons?i=kubernetes,terraform,python,ansible,docker,linux,prometheus,grafana,aws,gcp&theme=dark" alt="skill icons" />

</div>

---

## Architecture

**Zero-Trust perimeter for FinTech workloads**

- Edge → WireGuard / Cloudflare Tunnel
- K3s + GitOps (declarative, auditable)
- Cilium network policy & identity
- Vault for secrets · least privilege by default
- Observability that proves control, not just uptime

*Systems that pass security review without freezing the roadmap.*

---

## Products

- **[152Guard / AEGIS](https://152guard.space)** — AI Data Security Gateway: PII redaction, policy, and audit before model egress
- **[FTOPS](https://ftops.space)** — Infra control plane: MikroTik, private VPN mesh, corporate AI with change audit
- **[AutoHarden](https://github.com/ranas-mukminov/AutoHarden-Toolkit)** — CIS-oriented server hardening automation
- **[Secure K3s Starter](https://github.com/ranas-mukminov/Secure-K3s-GitOps-Template)** — Production-ready K3s + GitOps template

Brand: **[Run_as_daemon](https://run-as-daemon.dev)** · HQ: **[run-as-daemon.pro](https://run-as-daemon.pro)**

---

## Open Source

Pinned tooling you can clone today:

- [**Cloud-IAM-Optimizer**](https://github.com/ranas-mukminov/Cloud-IAM-Optimizer) — AWS/GCP IAM least-privilege auditor
- [**Kube-Simple-Audit**](https://github.com/ranas-mukminov/Kube-Simple-Audit) — 5-second K8s sanity check (`kubectl` + `jq`)
- [**k8s-fintech-baseline**](https://github.com/ranas-mukminov/k8s-fintech-baseline) — Kyverno PSS, NetworkPolicy, RBAC patterns for FinTech
- [**ssh-harden**](https://github.com/ranas-mukminov/ssh-harden) — minimal CIS-oriented `sshd_config` helper
- [**152fz-compliance-as-code**](https://github.com/ranas-mukminov/152fz-compliance-as-code) — 152-FZ oriented as-code practices

---

## Services

Engagements that ship architecture, not slide decks.

- **15-min Architecture Review** — Scope risk, stack fit, next concrete step
- **Zero-Trust K3s Sprint** — Hardened cluster + GitOps baseline
- **152Guard / AI Gateway** — In-jurisdiction AI path with redaction & audit
- **FTOPS Mesh** — Private site-to-site VPN + change control
- **Hardening & baselines** — AutoHarden + FinTech K8s policy pack

Prefer Telegram for speed · LinkedIn for intros.

---

## Reference topology

Vertical flow (reads cleanly on mobile):

1. **Client / API**
2. ↓ **Cloudflare Edge**
3. ↓ **WireGuard Gateway**
4. ↓ **Zero-Trust cluster** (K3s + GitOps)
   - Cilium Policy
   - Vault Secrets
   - Grafana / Audit
5. ↓ **152Guard / AI Gateway**

**Compact model:** edge trust → encrypted ingress → identity-aware mesh → secrets & evidence

---

<div align="center">

## Book a 15-min Architecture Review

**FinTech · High-load · Regulated data · Sovereign AI path**

<br/>

[![Book via Telegram](https://img.shields.io/badge/Book_15--min_Review-Telegram-0A0A0A?style=for-the-badge&logo=telegram&logoColor=26A5E4)](https://t.me/en_run_as_daemon_dev)
[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A0A0A?style=for-the-badge&logo=linkedin&logoColor=0A66C2)](https://www.linkedin.com/in/ranas-mukminov/)
[![Open HQ](https://img.shields.io/badge/Open_run--as--daemon.pro-0A0A0A?style=for-the-badge&logo=vercel&logoColor=00E5A8)](https://run-as-daemon.pro)

<br/>

<sub>
<a href="https://run-as-daemon.dev">run-as-daemon.dev</a> ·
<a href="https://run-as-daemon.pro">run-as-daemon.pro</a> ·
<a href="https://ftops.space">ftops.space</a> ·
<a href="https://152guard.space">152guard.space</a>
</sub>

</div>

---

<details>
<summary><strong>Activity</strong> (optional widgets)</summary>
<br/>
<div align="center">

<img height="160" src="https://github-readme-stats.vercel.app/api?username=ranas-mukminov&show_icons=true&theme=dark&hide_border=true&bg_color=0D1117&title_color=00E5A8&icon_color=00E5A8&text_color=C9D1D9&count_private=true" alt="GitHub stats" />
<img height="160" src="https://github-readme-streak-stats.herokuapp.com/?user=ranas-mukminov&theme=dark&hide_border=true&background=0D1117&ring=00E5A8&fire=00E5A8&currStreakLabel=00E5A8" alt="GitHub streak" />

</div>
</details>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ranas-mukminov&style=flat-square&color=00E5A8" alt="profile views" />
</p>
