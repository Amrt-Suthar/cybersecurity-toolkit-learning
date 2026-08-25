# 🔎 Subfinder

> Passive subdomain enumeration — ProjectDiscovery

## 🎯 What is Subfinder?

Subfinder is a passive subdomain enumeration tool by ProjectDiscovery
used to discover publicly available subdomains of a target domain
through multiple passive sources.

## 🧠 What I Learned

- Passive subdomain enumeration
- Difference between discovery and DNS resolution
- Source selection and source attribution
- JSONL output and automation
- Provider configuration and API credentials
- Rate limiting
- Recursive enumeration
- Filtering and output management
- Timeout and execution-time controls

## 🔗 Where Subfinder Fits

```text
Target Domain
      ↓
  Subfinder
      ↓
Discovered Subdomains
      ↓
     DNSx
      ↓
Resolvable Hosts
      ↓
    HTTPx
      ↓
HTTP/HTTPS Services
