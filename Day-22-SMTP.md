# Day 22 – SMTP (Simple Mail Transfer Protocol)

## Topics Covered
- What is SMTP
- Purpose of SMTP
- How SMTP works
- SMTP architecture
- Common SMTP commands
- SMTP ports
- SMTP with encryption
- Security risks in SMTP
- Protection mechanisms

## Explanation
SMTP (Simple Mail Transfer Protocol) is an application-layer protocol used for sending emails from one server to another and from email clients to mail servers.

SMTP is responsible only for sending emails. Receiving emails is handled by other protocols such as POP3 or IMAP.

SMTP works using a client-server model. The sending mail server acts as an SMTP client, while the receiving mail server acts as an SMTP server.

### How SMTP Works (Step-by-Step)
1. Email client connects to SMTP server.
2. Server identifies itself.
3. Client specifies sender email address.
4. Client specifies recipient email address.
5. Email content is transferred.
6. Server accepts and queues the message.
7. Message is delivered to recipient mail server.

### SMTP Architecture
- Mail User Agent (MUA): Email client (Gmail, Outlook)
- Mail Transfer Agent (MTA): Sends email between servers
- Mail Delivery Agent (MDA): Delivers email to mailbox

### Common SMTP Commands
- HELO / EHLO
- MAIL FROM
- RCPT TO
- DATA
- QUIT

### SMTP Ports
- 25  – Default SMTP
- 587 – SMTP with STARTTLS (recommended)
- 465 – SMTP over SSL/TLS

### SMTP with Encryption
Modern SMTP uses encryption to protect data:
- SSL/TLS
- STARTTLS

Encryption prevents attackers from reading or modifying emails during transmission.

## Why This Matters in Cybersecurity
SMTP is widely targeted by attackers.
Used heavily in phishing campaigns.
Misconfigured SMTP servers enable spam relays.
Email-based attacks often start security breaches.

## Common SMTP-Based Attacks
- Phishing
- Email spoofing
- Spam relay abuse
- Malware delivery

## Security Best Practices
- Use port 587 with STARTTLS.
- Disable open mail relays.
- Enable SPF, DKIM, and DMARC.
- Use strong authentication.
- Monitor mail logs.

## My Key Takeaway
SMTP is the backbone of email communication and must be properly secured to prevent abuse.
