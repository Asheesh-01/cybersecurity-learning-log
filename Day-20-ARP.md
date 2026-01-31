# Day 20 – ARP (Address Resolution Protocol)

## Topics Covered
- What is ARP
- Purpose of ARP
- How ARP works
- ARP packet structure
- ARP cache
- Types of ARP
- ARP in cybersecurity
- Common ARP-based attacks
- Defensive measures

## Explanation
ARP (Address Resolution Protocol) is a network protocol used to map an IP address to a physical MAC address within a local area network (LAN).

Devices communicate on Ethernet networks using MAC addresses, but applications use IP addresses. ARP acts as a bridge between Layer 3 (Network layer) and Layer 2 (Data Link layer).

When a device wants to communicate with another device on the same network, it sends an ARP Request as a broadcast asking: "Who has this IP address?"  
The device owning that IP responds with an ARP Reply containing its MAC address.

The sender stores this information in its ARP cache to avoid repeated requests.

### How ARP Works (Step-by-Step)
1. Host checks its ARP cache.
2. If no entry exists, it broadcasts an ARP Request.
3. Target host replies with MAC address.
4. Entry is stored in ARP table.

### ARP Cache
ARP cache is a table that stores recently resolved IP-to-MAC mappings. Entries may be dynamic or static.

### Types of ARP
- ARP (Standard ARP)
- Gratuitous ARP
- Proxy ARP
- Reverse ARP (RARP)

Each type serves different network purposes.

## Why This Matters in Cybersecurity
ARP has no built-in authentication.
Attackers can exploit ARP to perform man-in-the-middle attacks.
ARP poisoning enables traffic interception and redirection.
Understanding ARP helps detect suspicious behavior.

## Common ARP-Based Attacks
- ARP Spoofing
- ARP Poisoning
- Man-in-the-Middle (MITM)
- Session Hijacking

## Defensive Measures
- Use static ARP entries where possible.
- Enable Dynamic ARP Inspection (DAI).
- Monitor ARP traffic.
- Use network segmentation.

## My Key Takeaway
ARP is essential for local communication but must be protected against manipulation.
