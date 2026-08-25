# 🌐 DNSx

> Fast and multi-purpose DNS toolkit by ProjectDiscovery.

## 🎯 What is DNSx?

DNSx is a DNS querying and resolution tool used to resolve hostnames
and retrieve DNS records such as **A, AAAA, and CNAME** records.

In a reconnaissance workflow, DNSx helps determine which discovered
hostnames are **DNS-resolvable** and can provide useful DNS information
about them.

---

## 🧠 What I Learned

- DNS resolution and why it does not mean a website is live
- Resolving individual hosts and host lists
- Using DNSx with Subfinder
- A, AAAA, and CNAME records
- DNS response output with `-resp`
- Response-only output with `-resp-only`
- Custom DNS resolvers with `-r`
- Resolver lists with `-rL`
- Clean output with `-silent`
- Saving results to files
- Building reconnaissance pipelines

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
HTTP/HTTPS Services
