# Secure Multi-Site Enterprise Network Infrastructure

## Overview
A high-availability, fully redundant, and secure multi-site enterprise network infrastructure designed and simulated using GNS3. This architecture emulates a real-world production environment connecting a Head Office (Cairo) and a Branch Office (Alexandria) through a multi-provider ISP Core network, integrated with a centralized Windows Server.


## Features
- Multi-VLAN Segmentation
- Inter-VLAN Routing
- Basic BGP Peering (iBgp)
- OSPF Routing
- DMVPN (Dynamic Multipoint VPN) over OSPF
- Layer 3 EtherChannel (Link Aggregation)
- VRRP / HSRP Redundancy (Virtual IP: 192.168.x.100)
- NAT / PAT Configuration
- DNS server
- Spanning tree (primary,secondary)
- Layer 2 Etherchannel  
- Port Security (MAC-based Control)
- Dhcp Snooping
- STP Guarding (BPDU Guard & Root Guard)
- Secure Management (SSH & ACL-restricted Telnet)
- Windows Server Active Directory (Domain Controller)
- Centralized DHCP Server Scopes

## Project Files
- **Documentation Folder** (Contains technical report PDF)
- **Screenshots Folder** (Network layout and verification pings)

## Author
Youssef Araby
