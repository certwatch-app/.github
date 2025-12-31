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
  <a href="https://certwatch.app">Website</a> •
  <a href="https://docs.certwatch.app">Docs</a> •
  <a href="https://certwatch.app/blog">Blog</a> •
  <a href="https://discord.gg/ndA6jd5ReR">Discord</a> •
  <a href="https://x.com/certwatchapp">Twitter</a>
</p>

---

## 🔍 What is CertWatch?

CertWatch monitors your SSL/TLS certificates and alerts you before they expire — via **Slack**, **Email**, **PagerDuty**, **Microsoft Teams**, or **Webhooks**.

- ✅ **Certificate Expiration Monitoring** — Get alerts at 30, 14, 7, and 1 day before expiry
- ✅ **Chain Validation** — Detect incomplete certificate chains that break API clients
- ✅ **Weak Crypto Detection** — Identify SHA-1, short RSA keys, and outdated TLS versions
- ✅ **OCSP/CRL Revocation Checks** — Know if your certificate has been revoked
- ✅ **Team Collaboration** — Role-based access for your entire organization

---

## 🛠️ Open Source

### [cw-agent](https://github.com/certwatch-app/cw-agent)

Monitor certificates on private networks and Kubernetes clusters with our open-source agent.
```bash
# Homebrew (macOS/Linux)
brew install certwatch-app/tap/cw-agent

# Go
go install github.com/certwatch-app/cw-agent/cmd/cw-agent@latest

# Docker
docker pull ghcr.io/certwatch-app/cw-agent:latest
```

[![CI](https://github.com/certwatch-app/cw-agent/actions/workflows/ci.yml/badge.svg)](https://github.com/certwatch-app/cw-agent/actions/workflows/ci.yml)
[![Go Report Card](https://goreportcard.com/badge/github.com/certwatch-app/cw-agent)](https://goreportcard.com/report/github.com/certwatch-app/cw-agent)

---

## 🧰 Free Tools

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

## 📚 Resources

- **[SSL Certificate Expiration Guide](https://certwatch.app/blog/ssl-certificate-expiration-guide)** — Complete guide for DevOps teams
- **[Fix SSL Certificate Chain Issues](https://certwatch.app/blog/fix-ssl-certificate-chain-issues)** — Troubleshooting guide for Nginx & Apache
- **[Documentation](https://docs.certwatch.app)** — Full platform documentation

---

## 🚀 Get Started

Sign up free at **[certwatch.app](https://certwatch.app)** and start monitoring your certificates in minutes.

---

<p align="center">
  <a href="https://certwatch.app">Website</a> •
  <a href="https://docs.certwatch.app">Docs</a> •
  <a href="https://certwatch.app/blog">Blog</a> •
  <a href="https://discord.gg/ndA6jd5ReR">Discord</a> •
  <a href="https://x.com/certwatchapp">Twitter</a>
</p>
```
