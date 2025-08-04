
# Task 1: Scan Local Network for Open Ports

## Objective
Discover open ports on devices in your local network and assess potential security risks using Nmap.

## Tools Used
- Nmap
- Wireshark (optional)

## Key Command Used
```bash
sudo nmap -sS 192.168.43.0/24 -oN scan_results.txt

