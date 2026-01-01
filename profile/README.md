<p align="center">
  <a href="https://certwatch.app">
    <img src="https://certwatch.app/certwatch-logo.png" alt="CertWatch" width="120" />
  </a>
</p>

<h1 align="center">CertWatch</h1>

<p align="center">
  <strong>SSL/TLS Certificate Monitoring for DevOps Teams</strong><br>
  Never let an expired certificate take down your site again.
</p>

<p align="center">
  <a href="https://certwatch.app">Website</a> &bull;
  <a href="https://docs.certwatch.app">Docs</a> &bull;
  <a href="https://certwatch.app/roadmap">Roadmap</a> &bull;
  <a href="https://certwatch.app/blog">Blog</a> &bull;
  <a href="https://discord.gg/ndA6jd5ReR">Discord</a> &bull;
  <a href="https://x.com/certwatchapp">Twitter</a>
</p>

---

## What is CertWatch?

CertWatch monitors your SSL/TLS certificates and alerts you before they expire — via **Slack**, **Email**, **PagerDuty**, **Microsoft Teams**, or **Webhooks**.

| Feature | Description |
|---------|-------------|
| **Expiration Monitoring** | Get alerts at 30, 14, 7, and 1 day before expiry |
| **Chain Validation** | Detect incomplete certificate chains that break API clients |
| **Weak Crypto Detection** | Identify SHA-1, short RSA keys, and outdated TLS versions |
| **Revocation Checks** | OCSP/CRL monitoring to know if certificates are revoked |
| **Private Network Scanning** | Monitor internal endpoints with our open-source agent |
| **Kubernetes Integration** | Auto-discover cert-manager certificates *(coming soon)* |
| **Team Collaboration** | Role-based access for your entire organization |

---

## Open Source

### [cw-agent](https://github.com/certwatch-app/cw-agent)

<p>
  <a href="https://github.com/certwatch-app/cw-agent/actions/workflows/ci.yml"><img src="https://github.com/certwatch-app/cw-agent/actions/workflows/ci.yml/badge.svg" alt="CI"></a>
  <a href="https://goreportcard.com/report/github.com/certwatch-app/cw-agent"><img src="https://goreportcard.com/badge/github.com/certwatch-app/cw-agent" alt="Go Report Card"></a>
  <a href="https://github.com/certwatch-app/cw-agent/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-Apache%202.0-blue.svg" alt="License"></a>
  <a href="https://artifacthub.io/packages/search?repo=cw-agent"><img src="https://img.shields.io/endpoint?url=https://artifacthub.io/badge/repository/cw-agent" alt="Artifact Hub"></a>
</p>

Monitor certificates on **private networks** and **Kubernetes clusters** with our open-source agent.

**Install:**

```bash
# Quick install (Linux/macOS)
curl -sSL https://certwatch.app/install.sh | bash

# Homebrew
brew install certwatch-app/tap/cw-agent

# Docker
docker run ghcr.io/certwatch-app/cw-agent:latest

# Kubernetes (Helm)
helm install cw-agent oci://ghcr.io/certwatch-app/helm-charts/cw-agent \
  --namespace certwatch --create-namespace \
  --set agent.name=my-cluster \
  --set apiKey.value=cw_your_api_key
```

**Helm Charts:**

| Chart | Description | Status |
|-------|-------------|--------|
| [cw-agent](https://github.com/certwatch-app/cw-agent/tree/main/charts/cw-agent) | Network certificate scanner | Available |
| cw-agent-certmanager | cert-manager integration | Coming soon |
| cw-stack | Umbrella chart (deploy one or both) | Coming soon |

---

## Free Tools

No signup required — use these tools right now:

| Tool | Description |
|------|-------------|
| [SSL Certificate Checker](https://certwatch.app/tools/ssl-checker) | Check any certificate's validity and expiration |
| [Certificate Decoder](https://certwatch.app/tools/cert-decoder) | Decode and inspect certificate details |
| [CSR Generator](https://certwatch.app/tools/csr-generator) | Generate certificate signing requests |
| [Security Headers Checker](https://certwatch.app/tools/security-headers) | Analyze HTTP security headers |
| [DNS Lookup](https://certwatch.app/tools/dns-lookup) | Query DNS records for any domain |
| [Uptime Checker](https://certwatch.app/tools/uptime-checker) | Check if a website is up |

---

## Resources

| Resource | Description |
|----------|-------------|
| [Documentation](https://docs.certwatch.app) | Full platform documentation |
| [Agent Guide](https://docs.certwatch.app/agent) | cw-agent setup and configuration |
| [SSL Expiration Guide](https://certwatch.app/blog/ssl-certificate-expiration-guide) | Complete guide for DevOps teams |
| [Fix Chain Issues](https://certwatch.app/blog/fix-ssl-certificate-chain-issues) | Troubleshooting for Nginx & Apache |

---

## Get Started

Sign up free at **[certwatch.app](https://certwatch.app)** — no credit card required.

<p align="center">
  <a href="https://certwatch.app">Website</a> &bull;
  <a href="https://docs.certwatch.app">Docs</a> &bull;
  <a href="https://certwatch.app/roadmap">Roadmap</a> &bull;
  <a href="https://certwatch.app/blog">Blog</a> &bull;
  <a href="https://discord.gg/ndA6jd5ReR">Discord</a> &bull;
  <a href="https://x.com/certwatchapp">Twitter</a>
</p>
