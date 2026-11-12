WEEK 2 – CYBERSECURITY & ETHICAL HACKING

Practical Project Report

Project Overview

This project focuses on learning cybersecurity and ethical hacking techniques using Kali Linux and Zenmap. The practical activities introduce footprinting, reconnaissance, DNS enumeration, web technology identification, and network scanning.

The purpose of this project is to understand how cybersecurity professionals collect information about networks and systems, identify active hosts, and analyze network infrastructure using security tools.

All practical activities should be conducted in an authorized laboratory environment or on systems for which permission has been granted.

---

Project Module 1: Footprinting & Reconnaissance Attacks with Multiple Kali Tools

Objective

To perform footprinting and reconnaissance on the website "networkwalks.com" using Kali Linux tools and collect publicly available information about its domain, web technologies, IP address, HTTP headers, firewall, and DNS records.

Tools Used

- WHOIS: Retrieves domain registration information, registrar details, registration dates, and name servers.
- WhatWeb: Identifies web technologies, server information, and software running on a website.
- Nslookup: Resolves a domain name to its IP address.
- Curl: Retrieves HTTP response headers from a website.
- Wafw00f: Identifies the presence of a Web Application Firewall (WAF).
- DNSRecon: Enumerates DNS records, including name servers, mail servers, and other DNS information.

Tasks Performed

1. Used WHOIS to retrieve domain registration information.
2. Used WhatWeb to identify website technologies.
3. Used Nslookup to resolve the domain name to an IP address.
4. Used Curl to retrieve HTTP response headers.
5. Used Wafw00f to detect a Web Application Firewall.
6. Used DNSRecon to enumerate DNS records.

Commands Used

whois networkwalks.com

whatweb networkwalks.com

nslookup networkwalks.com

curl -I https://networkwalks.com

wafw00f networkwalks.com

dnsrecon -d networkwalks.com

Results

The practical guide identifies the following information:

- Domain registration and hosting information.
- Web technologies and software versions.
- Domain IP address.
- HTTP response headers.
- Web Application Firewall information.
- DNS records and mail server information.

The report instructs students to save screenshots and command outputs for each task.

Conclusion

This module demonstrates how reconnaissance tools can help cybersecurity professionals understand a website's publicly available infrastructure. The information collected provides a foundation for security assessment and helps organizations identify information that may expose their systems to potential risks.

---

Project Module 5: Network Scanning with Zenmap

Objective

To use Zenmap, the graphical interface for Nmap, to identify live hosts on a local network, determine their IP and MAC addresses, and generate a network topology diagram.

Tools Used

- Zenmap: Graphical network scanning application.
- Nmap: Network discovery and security scanning tool.
- Windows Command Prompt (CMD): Used to identify the local IP address and network configuration.
- ipconfig: Displays network configuration information.

Tasks Performed

1. Downloaded and installed Zenmap from the official Nmap website.
2. Identified the local IP address and LAN subnet using CMD.
3. Used Zenmap to perform a Ping Scan on the local subnet.
4. Identified the number of live hosts.
5. Collected the IP addresses of live hosts.
6. Identified the MAC addresses of live hosts.
7. Generated and saved the network topology diagram in PDF format.

Commands Used

To identify the local network configuration:

ipconfig

To display detailed network information, including the local MAC address:

ipconfig /all

Network Scanning

Zenmap was used to scan the local network subnet with the Ping Scan profile.

The instructor's example uses:

10.0.0.0/24

The scan results in the provided practical guide identified four live hosts, including the instructor's PC.

Results

The instructor's example reports:

Number of live hosts: 4

Host| IP Address
Host 1| 10.0.0.1
Host 2| 10.0.0.4
Host 3| 10.0.0.19
Host 4| 10.0.0.5

The practical guide also provides the MAC addresses of the four hosts.

Note: These are the instructor's example results. Actual results may differ depending on the local network configuration.

Network Topology

The Zenmap topology view was used to display the discovered network hosts.

The topology was saved in PDF format and included in the final practical report.

Conclusion

This module demonstrates how Zenmap can be used to discover active hosts and visualize a local network. The practical activities provide an introduction to network discovery, IP addressing, MAC addressing, and network topology analysis.

---

Overall Conclusion

The Week 2 cybersecurity practical introduced two important activities: footprinting and reconnaissance using Kali Linux tools, and network scanning using Zenmap.

Through these activities, I learned how to:

- Collect publicly available domain information.
- Identify website technologies and server information.
- Resolve domain names to IP addresses.
- Analyze HTTP response headers.
- Detect Web Application Firewalls.
- Enumerate DNS records.
- Identify live hosts on a local network.
- Retrieve IP and MAC addresses.
- Generate and save network topology diagrams.

These practical exercises improved my understanding of cybersecurity tools and their applications in network security assessment.

References

- Networkwalks: https://www.networkwalks.com/
- Nmap Official Website: https://nmap.org/
- Nmap Download Page: https://nmap.org/download.html

Project: Week 2 – Cybersecurity & Ethical Hacking
Modules: Project Module 1 and Project Module 5
Environment: Kali Linux, Windows PC, and Zenmap
Purpose: Educational cybersecurity and ethical hacking practical exercises 
