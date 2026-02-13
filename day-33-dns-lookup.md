# Day 33 – DNS Lookup

## What is DNS Lookup?

DNS lookup is the process of querying a DNS server to obtain the IP address or DNS records of a domain.

Example:
google.com → 142.250.x.x

---

## Tools Used

### 1️⃣ nslookup
Used to query DNS servers.

Example:
nslookup google.com

Check MX record:
nslookup -type=mx gmail.com

---

### 2️⃣ dig (Domain Information Groper)
Provides detailed DNS query output.

Example:
dig google.com

Check specific record:
dig google.com MX

---

## Common DNS Records Checked

- A → IPv4 address
- AAAA → IPv6 address
- MX → Mail server
- CNAME → Alias
- NS → Name server

---

## Practical Use in Cybersecurity

- Investigating phishing domains
- Checking suspicious domains
- Threat intelligence research
- SOC monitoring
- Incident response

---

## Why It Matters

DNS lookup is a daily tool for security analysts and network engineers.
Understanding it helps in detecting malicious infrastructure and domain abuse.
