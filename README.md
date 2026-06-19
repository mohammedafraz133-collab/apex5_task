# Task 5 – Capstone Project
## Network Vulnerability Assessment and Security Analysis of Metasploitable 2 Using Nmap

### Overview
This project was completed as part of Task 5 (Capstone Project) of the Cyber Security Internship Program. The objective was to perform a vulnerability assessment on a controlled test environment using Nmap and identify security weaknesses in a vulnerable machine (Metasploitable 2).

### Objectives
- Perform network reconnaissance.
- Discover live hosts and open ports.
- Identify running services and versions.
- Detect operating system information.
- Conduct vulnerability scanning using Nmap NSE scripts.
- Analyze findings and recommend mitigations.
- Simulate a basic incident response workflow.

### Scope
Target Machine:
- Metasploitable 2
- IP Address: 192.168.56.101

Scanning Machine:
- Kali Linux

### Tools Used
- Kali Linux
- Nmap
- Nmap NSE Scripts
- VirtualBox
- Metasploitable 2

### Methodology

#### 1. Network Discovery
```bash
ip a | sed -n '1,20p'
