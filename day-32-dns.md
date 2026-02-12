# Day 32 – DNS (Domain Name System)

## What is DNS?
DNS (Domain Name System) translates domain names into IP addresses.

Example:
google.com → 142.250.x.x

Without DNS, users would need to remember numeric IP addresses.

---

## Port Used
- UDP 53 (default)
- TCP 53 (zone transfer / large responses)

---

## Common DNS Record Types
- A → Maps domain to IPv4
- AAAA → Maps domain to IPv6
- MX → Mail server record
- CNAME → Alias record
- NS → Name server record

---

## How DNS Works
1. User enters domain
2. Resolver queries DNS server
3. Server responds with IP
4. Browser connects to that IP

---

## Common DNS Attacks
- DNS Spoofing
- Cache Poisoning
- DNS Tunneling
- DDoS Amplification

---

## Security Importance
- Blocks malicious domains
- Used in threat intelligence
- Helps in SOC monitoring
- Critical for network security

---

## Why It Matters
DNS is the backbone of internet communication and a major attack surface in cybersecurity.
