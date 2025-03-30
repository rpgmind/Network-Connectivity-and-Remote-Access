# Network Connectivity & Remote Access Report

## Summary:
This report details the process of verifying network connectivity between a Windows 10 VM and Kali Linux, identifying open ports, and establishing remote access using RDP.

## Steps Taken:
1. Verified Windows 10 and Kali Linux IP addresses.
2. Tested connectivity using ping.
3. Scanned Windows 10 for open ports using Nmap.
4. Verified RDP (port 3389) status.
5. Successfully connected to Windows 10 via Remmina (RDP).

## Findings:
- Windows 10 Firewall blocked ping requests. (this was remedied by configuring access rules for echo)
- Nmap revealed limited open ports (only those allowed by Windows Firewall).
- Remote Desktop Protocol (RDP) was accessible when enabled.

## Conclusion:
This project demonstrated basic network troubleshooting, security considerations, and remote access setup. It reinforces fundamental concepts covered in CompTIA A+, Network+, and Security+.
