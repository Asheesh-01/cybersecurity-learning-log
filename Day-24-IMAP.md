# Day 24 – IMAP (Internet Message Access Protocol)

## Topics Covered
- What is IMAP
- Purpose of IMAP
- How IMAP works
- IMAP architecture
- IMAP ports
- IMAP vs POP3
- Security risks
- Protection mechanisms

---

## What is IMAP
IMAP (Internet Message Access Protocol) is an application-layer protocol used to retrieve and manage emails directly on a mail server.

Unlike POP3, IMAP keeps emails stored on the server and synchronizes them across all devices.

---

## Purpose of IMAP
- Access emails from multiple devices
- Keep mailbox synchronized
- Manage folders remotely
- Enable real-time email access

---

## How IMAP Works
1. Client connects to IMAP server  
2. User authenticates  
3. Emails remain on server  
4. Client displays mailbox contents  
5. Any action syncs to server  

---

## IMAP Architecture
- Mail User Agent (MUA)  
- IMAP Server  
- Mail Storage  

---

## IMAP Ports
- 143 → Default IMAP  
- 993 → IMAP over SSL/TLS  

---

## IMAP vs POP3

IMAP:
- Emails stored on server  
- Sync across devices  
- Best for modern usage  

POP3:
- Emails downloaded locally  
- Often removed from server  
- Limited sync  

---

## Security Risks
- Credential sniffing
- Brute-force login
- Mailbox takeover
- Phishing delivery

---

## Protection Mechanisms
- Use SSL/TLS (port 993)
- Strong passwords
- Multi-factor authentication
- Disable plaintext authentication
- Monitor login activity

---

## Why IMAP Matters in Cybersecurity
Email accounts are high-value targets.  
IMAP security directly impacts data confidentiality and privacy.

---

## My Key Takeaway
IMAP enables flexible email access, but only when properly secured.
