# Day 40 – Transport Layer
## Cybersecurity Learning Journey

The **Transport Layer (Layer 4 of the OSI Model)** is responsible for end-to-end communication between devices.

It ensures that data is delivered reliably, in the correct order, and without errors.

---

## 🔹 Core Responsibilities

### 1. Segmentation
- Breaks large data into smaller segments
- Reassembles data at destination

### 2. Reliable Delivery
- Ensures packets arrive correctly
- Retransmits lost segments (TCP)

### 3. Flow Control
- Prevents sender from overwhelming receiver

### 4. Error Detection
- Detects corrupted segments

### 5. Port Addressing
- Uses port numbers to identify applications
- Example ports:
  - 80 (HTTP)
  - 443 (HTTPS)
  - 22 (SSH)
  - 53 (DNS)

---

## 🔹 Key Protocols

### TCP (Transmission Control Protocol)
- Connection-oriented
- Reliable
- Error-checked
- Used in web browsing and secure communications

### UDP (User Datagram Protocol)
- Connectionless
- Faster but less reliable
- Used in streaming, gaming, DNS

---

## 🔐 Security Importance

The Transport Layer plays a major role in:

- Port scanning detection
- Firewall filtering rules
- Intrusion detection systems (IDS)
- Secure communication (HTTPS runs over TCP)

---

## 🚨 Common Attacks Related to Layer 4

- Port scanning
- SYN flood attacks
- UDP flood attacks
- TCP reset attacks

---

## 🛡 Why It Matters in Cybersecurity

Monitoring Transport Layer activity helps:

- Identify suspicious open ports
- Detect abnormal traffic patterns
- Prevent denial-of-service attacks
- Secure sensitive services

---

### 🔄 OSI Model Progress
- Layer 1: Physical  
- Layer 2: Data Link  
- Layer 3: Network  
- Layer 4: Transport ✅  
- Layer 5: Session  
- Layer 6: Presentation  
- Layer 7: Application  

---

📌 Continuing the cybersecurity journey – one layer at a time.