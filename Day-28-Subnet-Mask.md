# Day 28 – Subnet Mask Fundamentals

## What is a Subnet Mask?
A subnet mask is a 32-bit number used with an IP address to identify:
- Network portion
- Host portion

It determines how many devices can exist in a network.

---

## Why Subnet Mask is Needed
- Divides large networks into smaller subnets
- Improves performance
- Enhances security
- Controls broadcast domains

---

## Common Subnet Masks

| CIDR | Subnet Mask        | Hosts |
|-----|--------------------|-------|
| /8  | 255.0.0.0          | ~16M  |
| /16 | 255.255.0.0        | 65,534|
| /24 | 255.255.255.0      | 254   |
| /26 | 255.255.255.192    | 62    |
| /28 | 255.255.255.240    | 14    |

---

## Binary Representation Example

IP Address:  
192.168.1.10  
Binary:  
11000000.10101000.00000001.00001010  

Subnet Mask:  
255.255.255.0  
Binary:  
11111111.11111111.11111111.00000000  

➡ Network bits = 1  
➡ Host bits = 0  

---

## CIDR Notation
CIDR (Classless Inter-Domain Routing):
- /24 = 24 network bits
- /16 = 16 network bits

Example:
192.168.1.0/24

---

## Subnetting Example

Given:
IP: 192.168.1.0/26  

- Subnet Mask: 255.255.255.192
- Block Size: 64
- Subnets:
  - 192.168.1.0 – 63
  - 192.168.1.64 – 127
  - 192.168.1.128 – 191
  - 192.168.1.192 – 255

---

## Cybersecurity Importance
- Network segmentation
- Limits lateral movement
- Used in firewall rules
- Helps detect abnormal traffic

---

## Used In
- Routers & switches
- Firewalls
- IDS/IPS
- SOC investigations

---

## Summary
Subnet mask is a foundation of secure networking.
Without subnetting, modern cybersecurity is impossible.
