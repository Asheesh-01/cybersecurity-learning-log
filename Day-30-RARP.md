# Day 30 – RARP (Reverse Address Resolution Protocol)

## What is RARP?
RARP is a network protocol used to obtain an IP address
when only the MAC address of a device is known.

It works in the opposite direction of ARP.

---

## ARP vs RARP

| Protocol | Resolves |
|--------|---------|
| ARP | IP → MAC |
| RARP | MAC → IP |

---

## Why RARP Was Used
- Diskless systems did not have storage
- Needed IP address at boot time
- MAC address was already known

---

## How RARP Works
1. Client sends RARP request with its MAC address
2. RARP server checks MAC–IP mapping
3. Server replies with assigned IP address

---

## Limitations of RARP
- Requires dedicated RARP server
- Not scalable
- No additional network configuration
- Works only within local network

---

## Replacement Protocols
- BOOTP
- DHCP (modern replacement)

---

## Cybersecurity Perspective
- Seen in legacy or lab environments
- Useful in packet analysis
- Helps understand protocol evolution
- Important for network forensics

---

## Summary
RARP is obsolete but important for learning
how modern address resolution systems evolved.
