# Day 17 – IANA

## Topics Covered
- Internet Assigned Numbers Authority (IANA) functions and responsibilities
- Protocol parameter assignments and registry management
- Root zone management and DNS coordination
- IP address allocation to Regional Internet Registries
- IANA's relationship with ICANN and global internet standards

## Explanation
The Internet Assigned Numbers Authority (IANA) is a department of ICANN responsible for coordinating critical internet protocol resources that ensure the internet functions properly. IANA manages three primary functions: domain names (DNS root zone), number resources (IP addresses and autonomous system numbers), and protocol assignments (port numbers, protocol parameters).

IANA maintains the authoritative root zone file for the Domain Name System, which serves as the master directory for all top-level domains worldwide. It allocates large blocks of IP addresses to five Regional Internet Registries (AFRINIC, APNIC, ARIN, LACNIC, RIPE NCC), who then distribute them to internet service providers and organizations within their regions.

The organization also manages protocol parameter registries, assigning standardized values for TCP/UDP port numbers, HTTP status codes, MIME types, and other protocol elements that enable interoperability across the global internet. IANA works closely with the Internet Engineering Task Force (IETF) and other standards bodies to ensure consistent technical implementation across internet infrastructure.

## Why This Matters in Cybersecurity
IANA's protocol parameter registries are essential for security professionals to identify legitimate services versus suspicious activity, as attackers often use non-standard or unassigned ports to evade detection systems.

Understanding IANA's IP address allocation structure helps security teams track malicious infrastructure geographically, coordinate with appropriate Regional Internet Registries during incident response, and implement accurate geolocation-based security controls.

IANA's management of the DNS root zone ensures the integrity of the entire domain name system, making it a critical trust anchor for DNSSEC implementation and protection against DNS hijacking attacks that could redirect millions of users.

## Real-World Application
- Security analysts reference IANA port number registry to identify suspicious network traffic using non-standard ports during threat hunting
- Incident responders use IANA's IP allocation database to trace attack origins and coordinate abuse reports with the correct Regional Internet Registry
- Network security teams implement firewall rules based on IANA-assigned protocol numbers and well-known port assignments

## Tools & Resources
- IANA Protocol Registry: https://www.iana.org/protocols
- IANA Port Number Database: Official registry of TCP/UDP port assignments
- IANA Root Zone Database: Authoritative list of all top-level domains and delegations

## My Key Takeaway
IANA is the central coordinating authority for internet protocol resources—understanding its functions is foundational to comprehending how internet security infrastructure operates globally.