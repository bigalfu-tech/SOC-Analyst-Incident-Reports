## Title
Internal Network Scan

## Time
2026-03-17 01:22:44 UTC

## Summary
Source 10.10.44.23 (HR workstation) scanned 1,200 hosts targeting ports 22, 80, 443, and 3389 using Nmap SYN scan.

## Analysis
Unusual internal scanning activity from an HR workstation indicates potential reconnaissance for lateral movement or vulnerability discovery.

## Classification
- Incident Type: Internal Reconnaissance  
- Severity: High  
- Confidence Level: High  
- Disposition: True Positive  

## Recommendation Action
- Isolate the source host  
- Review recent user activity on the workstation  
- Scan for malware or scripts performing the scans  
- Alert SOC and monitor network scanning attempts
