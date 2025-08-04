# Task 1: Scan Your Local Network for Open Ports 🔍

## Objective:
To discover open ports in a local network and understand network exposure using Nmap.

## Tools Used:
- Nmap
- Wireshark (optional)

## Steps Followed:
1. Installed Nmap on Windows.
2. Identified local IP: `192.168.1.7`.
3. Ran TCP SYN scan:  
4. Identified open ports and their services:
- **135/tcp** - MSRPC
- **139/tcp** - NetBIOS
- **445/tcp** - Microsoft-DS (SMB)
- **6881/tcp** - BitTorrent tracker

5. Saved scan results as `scan_results.txt`.

## Security Analysis:
- Ports 135, 139, 445 are common in Windows and can be vulnerable to exploits (e.g., EternalBlue).
- Port 6881 indicates a BitTorrent client; risky in secure environments.

## Outcome:
✅ Understood network reconnaissance and potential exposure of local devices.

