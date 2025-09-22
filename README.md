# Network-Scanning-usingnmap
Cybersecurity internship task: Network scanning with Nmap/Zenmap
# Network Scanning Task

## Overview
This repository contains my work for **Cybersecurity Internship – Task 1**.  
The objective was to use **Nmap/Zenmap** to scan my local network, identify open ports, and understand potential security risks.

---

## Steps I Followed
1. Installed **Nmap/Zenmap** from [nmap.org](https://nmap.org).
2. Found my local IP range:
   - IPv4 Address: `192.168.xx.x`
   - Subnet Mask: `255.255.255.0`
   - Network Range: `192.168.xx.0/24`
3. Ran a TCP SYN scan:
   ```bash
   nmap -sS 192.168.xx.0/24
