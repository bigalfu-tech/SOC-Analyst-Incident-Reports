## Title
DNS Enumeration Activity

## Time
2026-03-20 14:33:02 UTC

## Summary
4,500 DNS queries in 7 minutes for *.internal.bank.local from a compromised web server. NXDOMAIN responses spiked.

## Analysis
The query volume and pattern indicate automated DNS enumeration, likely to discover internal hosts and services for further attacks.

## Classification
- Incident Type: Reconnaissance / DNS Enumeration  
- Severity: High  
- Confidence Level: High  
- Disposition: True Positive  

## Recommendation Action
- Isolate compromised web server  
- Review logs for further scanning activity  
- Patch and secure DNS infrastructure  
- Monitor for follow-up attacks
