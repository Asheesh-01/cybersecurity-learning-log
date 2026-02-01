# Day 21 – Port Numbers

## Topics Covered
- What are port numbers
- Why ports are needed
- Port number ranges
- Common well-known ports
- TCP vs UDP ports
- Ports and services relationship
- Port scanning
- Security risks related to ports
- Port hardening techniques

## Explanation
A port number is a logical identifier used in computer networking to specify a particular service or application running on a device.

Every device on a network has an IP address. However, multiple applications can run on the same device at the same time. Ports allow the operating system to distinguish between these applications.

Ports work together with IP addresses and transport protocols (TCP or UDP) to form a socket.  
Example:
192.168.1.10:80  
Here, 80 is the port number for HTTP.

### Why Ports Are Needed
Ports allow:
- Web servers, mail servers, and databases to run on the same machine.
- Proper delivery of data to the correct application.
- Simultaneous network communication.

Without ports, network communication would be chaotic.

### Port Number Ranges
Ports are divided into three main ranges:

1. Well-known ports (0–1023)  
Reserved for standard services.

2. Registered ports (1024–49151)  
Used by specific applications.

3. Dynamic / Private ports (49152–65535)  
Used temporarily by client systems.

### Common Well-Known Ports
- 21  – FTP  
- 22  – SSH  
- 23  – Telnet  
- 25  – SMTP  
- 53  – DNS  
- 80  – HTTP  
- 110 – POP3  
- 143 – IMAP  
- 443 – HTTPS  

### TCP vs UDP Ports
TCP ports provide reliable, connection-oriented communication.  
UDP ports provide fast, connectionless communication.

Many services use specific ports over TCP or UDP depending on their design.

### Ports and Services
Each network service listens on a specific port.  
For example:
- Web server listens on port 80 or 443.
- SSH server listens on port 22.

If a service is not running, its port should not be open.

### Port Scanning
Attackers use tools like Nmap to scan ports to discover:
- Open ports
- Running services
- Possible vulnerabilities

This is often the first step in an attack.

## Why This Matters in Cybersecurity
Open ports increase attack surface.
Unused open ports are high-risk.
Misconfigured ports lead to exploitation.
Port awareness helps detect malicious activity.

## Security Best Practices
- Close unused ports.
- Use firewalls to restrict access.
- Change default ports where appropriate.
- Monitor open ports regularly.
- Use intrusion detection systems.

## My Key Takeaway
Port numbers control how services communicate and securing them reduces attack opportunities.
