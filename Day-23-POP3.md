# Day 23 – POP3 (Post Office Protocol v3)

## Topics Covered
- What is POP3
- Purpose of POP3
- How POP3 works
- POP3 architecture
- POP3 commands
- POP3 ports
- POP3 vs IMAP
- Security risks in POP3
- Protection mechanisms

## Explanation
POP3 (Post Office Protocol version 3) is an application-layer protocol used by email clients to retrieve emails from a mail server.

POP3 is mainly designed for offline email access. Emails are downloaded from the server to the client device and usually removed from the server after retrieval.

POP3 follows a client-server model where the email client acts as a POP3 client and the mail server acts as a POP3 server.

### How POP3 Works (Step-by-Step)
1. Email client connects to POP3 server.
2. Client authenticates using username and password.
3. Server provides list of messages.
4. Client downloads selected emails.
5. Emails may be deleted from server.
6. Connection is closed.

### POP3 Architecture
- Mail User Agent (MUA): Email client  
- POP3 Server: Stores user mailbox  

### Common POP3 Commands
- USER
- PASS
- STAT
- LIST
- RETR
- DELE
- QUIT

### POP3 Ports
- 110 – Default POP3  
- 995 – POP3 over SSL/TLS  

### POP3 vs IMAP
POP3 downloads emails locally and often deletes them from server.  
IMAP keeps emails on server and synchronizes across devices.

POP3 is simple and lightweight, while IMAP is more flexible.

## Why This Matters in Cybersecurity
POP3 credentials can be intercepted if unencrypted.
Compromised POP3 access leads to email account takeover.
Emails often contain sensitive information.

## Common POP3-Based Attacks
- Credential sniffing
- Brute-force login attempts
- Mailbox compromise
- Malware delivery

## Security Best Practices
- Use port 995 with SSL/TLS.
- Disable plaintext POP3.
- Enforce strong passwords.
- Enable multi-factor authentication.
- Monitor login activity.

## My Key Takeaway
POP3 enables email retrieval, but must always be protected with encryption.
