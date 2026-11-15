

Purpose

Kali Linux

Operating system for reconnaissance activities

WHOIS

Domain registration information gathering

WhatWeb

Website technology fingerprinting

Nslookup

Domain-to-IP address resolution

cURL

HTTP response header inspection

Wafw00f

Web Application Firewall detection

DNSRecon

DNS record enumeration

Zenmap

Network discovery and host scanning

Nmap

Network scanning engine

Windows CMD

Checking local network configuration

Task 1: Footprinting & Reconnaissance

Target: networkwalks.com

I used six different tools to collect information about the target domain.

Tool

Activity

Key Finding

WHOIS

Domain information gathering

Retrieved publicly available registration and name server information

WhatWeb

Technology fingerprinting

Identified WordPress 7.0.4 and WP Download Manager 3.3.58

Nslookup

DNS resolution

Identified IP address: 192.232.216.135

cURL

HTTP header inspection

Identified HTTP response information and /wp-json/ endpoint

Wafw00f

WAF detection

Identified ModSecurity (SpiderLabs)

DNSRecon

DNS enumeration

Collected DNS, mail and service-related records

Learning Outcomes

Learned how to gather publicly available information about a website.

Understood how DNS resolution works.

Gained experience identifying website technologies.

Learned how to inspect HTTP response headers.

Explored Web Application Firewall detection.

Practiced DNS enumeration using Kali Linux.

Task 2: Network Scanning with Zenmap

For this activity, I used Zenmap to perform a Ping Scan on my local network.

Steps Performed

Used Windows Command Prompt to check network configuration with ipconfig.

Identified the relevant network range.

Opened Zenmap and entered the target network range.

Selected the Ping Scan option.

Executed the scan to identify active hosts.

Reviewed the scan results.

Explored the Topology section to visualize the discovered network.

Scan Results

The scan identified one active host:

No.

IP Address

Status

1

192.168.56.1

Detected

Learning Outcomes

Learned how to identify local network configurations.

Practiced host discovery using Zenmap.

Understood how Ping Scans work.

Explored network topology visualization.

Gained experience analyzing network scan results.

Risk Analysis

The practical exercises highlighted several potential security observations:

Publicly visible website technology information can help attackers identify software versions.

Exposed DNS information can provide insight into an organization's infrastructure.

HTTP response headers may reveal technical details.

Identifying WAF technologies provides information about website security architecture.

Regular network scanning helps organizations identify active and unfamiliar devices.

Note: These observations represent potential security risks and do not confirm the presence of vulnerabilities.

Security Recommendations

Regularly review publicly exposed website information.

Keep CMS platforms and plugins updated.

Avoid exposing unnecessary technical information through HTTP headers.

Review DNS records periodically.

Properly configure and monitor Web Application Firewalls.

Perform regular internal network scans.

Investigate unfamiliar devices connected to the network.

Maintain updated network documentation.

Conduct reconnaissance and scanning only with proper authorization.

Repository Structure

Week-02-Cybersecurity-Internship/
│
├── README.md
│
├── Footprinting-and-Reconnaissance/
│   ├── WHOIS/
│   ├── WhatWeb/
│   ├── Nslookup/
│   ├── Curl/
│   ├── Wafw00f/
│   └── DNSRecon/
│
├── Network-Scanning/
│   ├── Zenmap-Scan/
│   └── Network-Topology/
│
└── Report/
    └── Week-2-Internship-Report.pdf

The structure above is a suggested organization for the repository. Add the folders and evidence files as applicable.

Disclaimer

This project was completed for educational and cybersecurity training purposes as part of my internship at Networkwalks.

All scanning and reconnaissance activities should only be performed against systems and networks that you own or have explicit authorization to test.

The information in this repository must not be used for unauthorized access, malicious activities, or any violation of applicable laws.

Week: 02

Learning by doing, one security tool at a time.
