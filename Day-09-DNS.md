# Day 09 – DNS

## Topics Covered
- What DNS is
- Purpose of DNS
- DNS resolution process
- Common DNS record types
- DNS server hierarchy

## Explanation
DNS stands for Domain Name System and it is used to translate human-readable domain names into IP addresses that machines understand. Instead of remembering numerical IP addresses, users can access websites using simple domain names.

When a user enters a domain name, the DNS resolver first checks the local cache. If the record is not found, it queries the root DNS server, then the top-level domain server, and finally the authoritative DNS server to obtain the correct IP address.

DNS uses different record types such as A, AAAA, CNAME, MX, and NS records to provide information for routing traffic, email delivery, and domain management across the network.

## Why This Matters in Cybersecurity
DNS is a common target for attacks such as DNS spoofing and cache poisoning.
Many phishing and malware campaigns rely on DNS to redirect traffic.
Monitoring DNS activity helps identify malicious domains and suspicious behavior.

## My Key Takeaway
DNS is a critical internet service that directly impacts both accessibility and security.
