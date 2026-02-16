# Day 35 – NAT (Network Address Translation)

## What is NAT?

NAT translates private IP addresses into public IP addresses.
It allows multiple devices in a private network to access the internet using fewer public IPs.

---

## Why NAT is Needed

- IPv4 address exhaustion
- Hides internal network
- Reduces cost of public IP allocation

---

## Types of NAT

### 1️⃣ Static NAT
- One-to-one mapping
- Used for hosting internal servers

### 2️⃣ Dynamic NAT
- Many-to-many mapping
- Uses a pool of public IP addresses

### 3️⃣ PAT (Port Address Translation)
- Many-to-one mapping
- Uses port numbers
- Most common type (home routers)

---

## How NAT Works (Example)

Private IP: 192.168.1.10  
Public IP: 203.0.113.5  

Router replaces private IP with public IP before sending packet to internet.

---

## Advantages

- Conserves IPv4 addresses
- Adds basic security layer
- Allows internal network scalability

---

## Limitations

- Breaks end-to-end connectivity
- Not a full security solution
- Can complicate logging

---

## Why It Matters in Cybersecurity

- Used in firewall architecture
- Important in log analysis
- Critical in network investigations
- Helps understand traffic flow
