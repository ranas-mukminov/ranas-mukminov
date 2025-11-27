# 🛡️ Ranas Security Stack
### Automated. Invisible. Secure by Design.

I don't just "fix servers". I architect **Zero-Trust Infrastructure** for FinTech and High-Load projects using Kubernetes and GitOps.
My goal is to build systems that secure themselves without slowing down developers.

---

## 🛠️ Security Architecture

This is the standard **Ranas Security Stack** topology I implement:

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
