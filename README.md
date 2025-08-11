# Task - 5 | Wireshark Packet Capture and Protocol Analysis

## Overview
This project involves analyzing network traffic captured in a controlled penetration testing lab environment. The setup used **Kali Linux** as the attacker machine and **Metasploitable 2** as the target, both connected via a VMware Host-Only Adapter (isolated virtual LAN). The objective was to study basic network protocols, identify insecure communications, and understand their behavior through packet captures.

## Captures Performed
1. **Nmap Scan on Metasploitable 2**  
   - Identified open ports, running services, and service banners.
   - Traffic captured to observe scanning patterns.

2. **FTP Anonymous Login**  
   - Connected to Metasploitable 2 FTP service using anonymous credentials.
   - Demonstrated how FTP transmits login credentials and commands in plain text.

3. **DVWA Login over HTTP**  
   - Logged into the Damn Vulnerable Web Application (DVWA) on Metasploitable 2.
   - Captured HTTP POST request containing username and password in plain text.

## Tools Used
- **Wireshark** – Packet capture and protocol analysis.
- **Nmap** – Network scanning.
- **VMware Workstation** – Virtualization platform.

## Purpose
This analysis highlights how different protocols function, demonstrates the security risks of unencrypted communications, and reinforces understanding of network traffic behavior in a safe lab environment.
