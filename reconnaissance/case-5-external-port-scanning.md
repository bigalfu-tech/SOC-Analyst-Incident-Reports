## Title
External Port Scanning of Perimeter

## Time
2026-03-30 04:05:38 UTC

## Summary
Source IP 103.245.222.17 performed 18,000 connection attempts across all TCP ports targeting the bank’s public IP range.

## Analysis
Full TCP port scan from an external IP indicates aggressive reconnaissance, possibly preceding targeted attacks. High volume suggests automated scanning tool.

## Classification
- Incident Type: Reconnaissance / External Port Scan  
- Severity: High  
- Confidence Level: High  
- Disposition: True Positive  

## Recommendation Action
- Block or rate-limit offending IP  
- Monitor firewall logs for repeat attempts  
- Alert SOC for potential follow-up attacks
