# Lab 03 – VLAN Management and SSH Remote Access

## Overview
This lab demonstrates configuring and managing two Cisco switches using VLANs, IP addressing, and secure remote access through SSH in Cisco Packet Tracer.

Two Cisco Catalyst 2960 switches were configured with a dedicated management VLAN. Connectivity between the switches was verified using ICMP ping testing, followed by successful remote administration using SSH.

## Skills Demonstrated
- Cisco Packet Tracer
- Cisco IOS CLI
- VLAN configuration
- Switch Virtual Interfaces (SVI)
- IPv4 addressing and subnetting
- Inter-switch connectivity
- SSH Version 2
- RSA key generation
- Local user authentication
- ICMP/Ping connectivity testing
- Remote switch administration
- Network troubleshooting
- Saving and verifying configurations

## Network Configuration
- Management VLAN: VLAN 10 (MGMT)
- SW01 Management IP: 10.0.10.5/24
- SW02 Management IP: 10.0.10.6/24
- Default Gateway: 10.0.10.1
- SSH Version: 2
- RSA Encryption: 2048-bit

## Verification
- Verified communication between SW01 and SW02 using ping
- Achieved 100% successful ICMP connectivity
- Successfully established an SSH session from SW01 to SW02
- Saved the completed configurations to startup-config

## Files
- `Hersam-lab03.pkt` – Cisco Packet Tracer network file
- `Hersam-lab03-Screenshot1-Ping.png` – Successful connectivity verification
- `Hersam-lab03-Screenshot2-SSH.png` – Successful SSH remote-access verification
