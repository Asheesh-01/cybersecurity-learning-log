# Day 29 – Broadcast Address

## What is a Broadcast Address?
A broadcast address is an IP address used to send data to
ALL devices within a subnet.

It is the LAST IP address of a subnet.

---

## Key Characteristics
- Used for one-to-all communication
- Cannot be assigned to any host
- Helps in network discovery
- Essential for routing protocols

---

## Example

IP Address: 192.168.1.10  
Subnet Mask: 255.255.255.0 (/24)

Network Address: 192.168.1.0  
Broadcast Address: 192.168.1.255  

---

## How Broadcast Address is Calculated
- Convert IP and subnet mask to binary
- All host bits set to 1
- Resulting address = broadcast

---

## Types of Broadcast

1. Limited Broadcast  
   - 255.255.255.255  
   - Sent within local network only

2. Directed Broadcast  
   - Sent to all hosts of a specific subnet  
   - Example: 192.168.1.255

---

## Cybersecurity Perspective
- Used by attackers for network scanning
- Excessive broadcast traffic may indicate:
  - Worm propagation
  - Misconfiguration
  - DDoS amplification

---

## Used In
- ARP requests
- DHCP discovery
- Routing updates
- Network troubleshooting

---

## Why It Matters in Cybersecurity
- Helps identify abnormal traffic
- Important for SOC monitoring
- Core networking foundation
