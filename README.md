# ptr.sh - v 1.3.0 - WIP
## PenTestRecon
```
a. Run all
1. Get all subdomains (assetfinder, subfinder)
2. Get amass subdomains (skipping...)
3. Handle redirects
4. Check scopes
5. Check for live domains (httprobe)
6. Check CSP
7. Take screenshots (gowitness)
8. Import in Burp (burp/proxy)
9. Quick host up check (nmap)
10. Get open ports (nmap)
11. Generate HTML output of open ports
12. Cleanup all files (domains/screenshots/nmap/csp)
13. Cleanup domains
14. Cleanup screenshots
15. Cleanup nmap scans
16.Cleanup CSP files
x. Exit
```

## Usage
```bash
./ptr.sh <url>
```
## nmap scan results
![image](https://github.com/user-attachments/assets/46a31c23-8a03-4460-9828-a8539bef7938)

## Workflow
The amass part has to be skipped because of the issue (crashing machine).
![PentesterReconTool](https://github.com/user-attachments/assets/87fcd76c-2ec1-4428-89f6-ca5a84b0f088)

