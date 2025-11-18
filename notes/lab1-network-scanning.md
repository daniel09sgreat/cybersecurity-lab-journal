# Lab 1: Network Scanning with Nmap

## Objective
Perform a network scan to identify open ports and services.

## Tools Used
- Kali Linux
- Nmap

## Steps
1. Installed Nmap on Kali Linux.
2. Ran the command:
   ```bash
   nmap -sV 162.241.216.11

**FINDINGS**
## Target
162.241.216.11
Resolves to: box5331.bluehost.com

## Result
The host is reachable and responding.
Open Ports
80/tcp – HTTP running on Apache
443/tcp – HTTPS running on Apache (SSL-enabled)

## What this means:
The server is basically a web hosting machine running Apache for both normal and encrypted web traffic. 
No unusual services exposed, no errors from the scan besides earlier retry limits.
