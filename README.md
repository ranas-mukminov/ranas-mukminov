# 🛡️ Ranas Security Stack
### Automated. Invisible. Secure by Design.

I don't just "fix servers". I architect **Zero-Trust Infrastructure** for FinTech and High-Load projects using Kubernetes and GitOps.

---

## 🚀 Core Products (Open Source)

| Product | Status | Description |
| :--- | :--- | :--- |
| **[Cloud-IAM-Optimizer](https://github.com/ranas-mukminov/Cloud-IAM-Optimizer)** | 🟢 **Stable** | **Identity Security.** Automated audit tool for AWS IAM. Finds dormant admins, MFA gaps, and old keys in <5s. |

---

## 🛠️ Tech Stack
## 🛠️ Security Architecture Stack

```mermaid
graph TD
    User([👤 Client / Traffic]) -->|HTTPS/443| CF[☁️ Cloudflare Edge]
    
    subgraph "Zero Trust Perimeter"
        CF -->|Tunnel| WG[🔐 WireGuard Gateway]
        WG -->|GitOps| K3s[☸️ K3s Cluster]
    end
    
    subgraph "Automated Defense"
        K3s -->|Scans| IAM[🐍 Cloud-IAM-Optimizer]
        K3s -->|Monitor| Grafana[📊 Grafana / Kuma]
    end
    
    style CF fill:#f96,stroke:#333,stroke-width:2px
    style K3s fill:#326ce5,stroke:#333,stroke-width:2px,color:#fff
    style IAM fill:#ffd343,stroke:#333,stroke-width:2px

---

### 📬 Need an Audit?
If you want to secure your infrastructure "by design" without slowing down your developers:

👉 **[Book a 15-min Architecture Review](https://run-as-daemon.dev/en/services/express-audit-hardening.html)**
