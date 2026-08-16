# OWASP Passive OSINT & External Attack Surface Assessment

## 🔎 Project Overview

A professional passive OSINT and external attack surface assessment of **OWASP.org** using publicly accessible information.

The assessment focused on identifying publicly observable DNS infrastructure, website intelligence, technology indicators, cloud infrastructure, TLS information, public digital footprint, security findings and recommendations.

> **Assessment Type:** Passive OSINT / External Attack Surface Assessment  
> **Target:** OWASP.org  
> **Authorization:** Publicly accessible information only  
> **Exploitation:** None performed

---

## 🎯 Objectives

- Identify publicly observable DNS records and infrastructure
- Enumerate relevant OWASP subdomains
- Analyze A, AAAA and CNAME records
- Analyze MX, TXT, SPF, DMARC and NS records
- Review website security headers
- Identify technology and infrastructure indicators
- Analyze TLS certificate information
- Document public digital footprint
- Identify security-relevant observations
- Assign risk ratings
- Provide security recommendations

---

## 🛠️ Tools & Techniques

| Tool / Technique | Purpose |
|---|---|
| DNSChecker | DNS record analysis |
| DNSViz | DNSSEC and DNS relationship analysis |
| cURL | HTTP response and header analysis |
| Browser | Website and TLS inspection |
| WHOIS / ASN information | Infrastructure ownership analysis |
| Passive OSINT | Public digital footprint analysis |

---

## 📋 Assessment Scope

### Domain & DNS Intelligence

- Domain information
- DNS records
- Nameservers
- DNSSEC status
- Email infrastructure
- SPF / DMARC
- Subdomain infrastructure
- IP / ASN ownership

### Website Intelligence

- HTTP response
- Security headers
- HTTPS configuration
- Redirect behavior
- robots.txt
- Content Security Policy
- Server and caching indicators

### Technology & Infrastructure

- CDN / hosting indicators
- Cloud infrastructure
- Third-party services
- Technology indicators
- TLS certificate information

### Public Digital Footprint

- Publicly observable domains and subdomains
- Third-party infrastructure
- Public services
- External dependencies

---

## 🔐 Key Security Observations

The assessment identified several publicly observable infrastructure and security configuration characteristics.

These observations were documented and evaluated based on their potential security relevance and exposure.

Detailed findings, evidence and risk ratings are available in the assessment report.

---

## 📊 Risk Rating

| Severity | Meaning |
|---|---|
| 🔴 Critical | Immediate and severe security impact |
| 🟠 High | Significant security risk |
| 🟡 Medium | Moderate security concern |
| 🔵 Low | Limited security impact |
| ⚪ Informational | Observation with no direct security impact |

---

## 📄 Full Assessment Report

[View the Full OSINT Assessment Report](./OSINT%20Investigation%20%26%20Digital%20Footprint%20Report.pdf)

---

## 🖼️ Evidence

Screenshots and supporting evidence collected during the assessment are available here:

[View Evidence](./Evidence/)

---

## 📁 Repository Structure

```text
owasp-passive-osint-assessment/
│
├── Evidence/
│   ├── DNS/
│   ├── Website/
│   ├── Technology/
│   └── Other Evidence
│
├── OSINT Investigation & Digital Footprint Report.pdf
│
└── README
```
## 👤 Author

**Vasu Dadhaniya**

Cybersecurity | OSINT | SOC | Security Research

GitHub: [@vasudadhaniya0](https://github.com/vasudadhaniya0)
