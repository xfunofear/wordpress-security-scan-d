# wordpress-security-scan-d
Wordpress Security Scan of - depravebhp.pl
This project contains the results of a security scan conducted on a WodrdPress-based website using Wpscan.
It is part of my cybersecurity learning journey, focusing on penetration testing, vulnerability enumeration, and secure configuration awareness.

## Tools Used
- WPScan
- Kali Linux (VirtualBox environment)
- Git + GitHub

## What Was Done
- Scanned WordPress site for:
  - Version detection
  - Outdated plugins and themes
  - Enumeration of users and configuration leaks
- Output saved in text file `scan_results.txt`

## Notes
This scan was conducted for educational and ethical hacking purposes. No unauthorized exploitation was performed.

## Example Command
```bash
wpscan --url https://example.com --api-token YOUR_API_TOKEN --enumerate vp,vt,u -o scan_results.txt
