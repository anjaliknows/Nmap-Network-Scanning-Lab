# Nmap Network Reconnaissance Lab

## About the Project

This project documents my hands-on learning of **Nmap (Network Mapper)** using Kali Linux. It focuses on network reconnaissance, host discovery, TCP and UDP port scanning, service detection, and basic operating-system fingerprinting.

The objective is to understand how network scanning works, interpret scan results, and document practical cybersecurity exercises.

## Objectives

- Understand Nmap and its role in network security.
- Identify responsive hosts on a local virtual network.
- Perform TCP port scanning and service/version detection.
- Compare default port scans with full TCP port scans.
- Explore UDP scanning and operating-system detection.
- Verify local services using Linux commands such as `ss` and `systemctl`.
- Document observations, troubleshooting steps, and results.

## Tools and Environment

- **Operating System:** Kali Linux
- **Network Scanner:** Nmap 7.99
- **Supporting Commands:** `ip`, `ss`, `systemctl`
- **Environment:** Virtual machine and local lab network

## Practical Exercises Completed

1. Verified the Nmap installation and version.
2. Inspected network interfaces and routing information.
3. Performed host discovery on the lab subnet.
4. Scanned common TCP ports and all TCP ports on localhost.
5. Used service/version detection with `-sV`.
6. Started and stopped the SSH service to observe port 22.
7. Scanned selected TCP ports: 22, 80, and 443.
8. Scanned the 20 most common UDP ports.
9. Attempted operating-system detection using `-O`.

## Key Learnings

- The difference between host discovery and port scanning.
- The meaning of open, closed, and filtered port states.
- The differences between TCP and UDP scanning.
- How service availability affects Nmap results.
- Why OS fingerprinting may not identify a specific operating system.
- How to compare Nmap results with local socket and service information.

## Documentation

The accompanying Word report contains the commands used, explanations of their options, terminal screenshots, observed results, troubleshooting notes, and conclusions.

**Report:** `Nmap_Network_Reconnaissance_Report_Updated.docx`

## Scope and Responsible Use

Scans were performed against localhost and the virtual lab network used for these exercises. Only scan systems and networks that you own or have explicit permission to assess.

## Future Learning

- Additional TCP scan techniques
- Nmap output formats and scan-result analysis
- Network mapping and scan optimisation
- Nmap Scripting Engine (NSE)
- Automated reporting of authorised scan results

---

*This repository is a learning portfolio documenting my progress in network reconnaissance and cybersecurity.*
