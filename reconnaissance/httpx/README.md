# 🌐 HTTPx

> Fast HTTP/HTTPS probing and web-service metadata collection by ProjectDiscovery.

## 🎯 What is HTTPx?

HTTPx is a fast HTTP/HTTPS probing tool used to identify and collect
information about web services.

It can help determine whether a hostname exposes an HTTP/HTTPS service
and collect useful metadata such as:

- HTTP status codes
- Page titles
- Web technologies
- Web server information
- IP addresses
- Redirects
- Structured JSON output

---

## 🧠 What I Learned

- HTTP/HTTPS service probing
- Understanding HTTP status codes
- Processing DNSx/Subfinder output
- Status code and page-title enumeration
- Technology detection
- Web-server identification
- IP discovery
- Redirect following
- Clean output for automation
- JSON/JSONL-style structured output
- Prioritizing web services for further investigation
- Understanding shared IP infrastructure

---

## 🔍 Core Concept

```text
Subfinder
    ↓
Discovered Subdomains
    ↓
DNSx
    ↓
DNS-Resolvable Hosts
    ↓
HTTPx
    ↓
HTTP/HTTPS Services + Metadata
