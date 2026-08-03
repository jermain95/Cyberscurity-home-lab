# Cybersecurity Home Lab

## Overview

This repository documents the development of my cybersecurity home lab. The goal of this project is to gain hands-on experience with networking, firewall administration, packet analysis, and Security Operations Center (SOC) operations using industry-standard tools.

---

## Objectives

- Build an enterprise-style cybersecurity lab
- Learn networking and firewall management
- Develop packet analysis skills
- Practice security monitoring and incident investigation
- Create a portfolio demonstrating hands-on cybersecurity experience

---

# Lab Environment

| Component | Status |
|-----------|--------|
| VMware Workstation Pro | ✅ Complete |
| pfSense Firewall | ✅ Complete |
| Windows 11 Workstation | ✅ Complete |
| Sysinternals Suite | ✅ Complete |
| Wireshark | ✅ Complete |
| Git & GitHub | ✅ Complete |

---

# Progress

## Phase 1 – Network Foundation

- Installed VMware Workstation Pro
- Created a pfSense virtual machine
- Installed pfSense CE
- Configured WAN and LAN interfaces
- Configured DHCP
- Verified Internet connectivity
- Verified DNS resolution
- Completed the pfSense setup wizard

---

## Windows 11 Workstation

- Created a Windows 11 virtual machine
- Installed Windows 11
- Connected the Windows VM to the pfSense LAN
- Installed VMware Tools
- Created a VMware snapshot for recovery

---

## SOC Workstation

Installed the following tools:

- Microsoft Sysinternals Suite
- Wireshark
- Npcap

---

## Network Analysis

Completed introductory packet analysis using Wireshark:

- Captured ICMP traffic
- Identified source and destination IP addresses
- Examined IPv4 packet headers
- Learned the TCP three-way handshake
- Performed basic DNS troubleshooting

---

# Skills Demonstrated

- VMware Virtualization
- pfSense Firewall Administration
- Windows 11 Administration
- DHCP Configuration
- DNS Troubleshooting
- TCP/IP Networking
- Wireshark Packet Analysis
- Git Version Control
- GitHub Repository Management

---

# Current Network Topology

Internet
        │
Home Router
        │
VMware NAT (VMnet8)
        │
pfSense Firewall
WAN: 192.168.x.x
LAN: 10.10.10.1
        │
VMnet2
        │
Windows 11 VM
10.10.10.100

---

# Next Steps

- Continue advanced Wireshark analysis
- Build a packet capture VM
- Learn tcpdump
- Install Kali Linux
- Deploy Wazuh SIEM
- Create incident response investigations
- Build threat hunting scenarios

---

## Author

**Quintin Sowell**
Cybersecurity Student | SOC Analyst Aspirant
