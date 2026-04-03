## Title
API Authentication Abuse

## Time
2026-03-25 00:44:52 UTC

## Summary
The `/api/v2/auth/login` endpoint received 2,431 requests in 5 minutes from rotating Tor IPs. Most returned 401, with occasional 200 responses. User-agent spoofed a mobile banking app.

## Analysis
High request rates from multiple IPs indicate automated abuse. Occasional successful responses suggest potential account compromise. Tor usage and spoofing show evasion techniques.

## Classification
- Incident Type: Brute Force / Credential Stuffing  
- Severity: High  
- Confidence Level: High  
- Disposition: True Positive  

## Recommendation Action
- Block malicious IPs and Tor exit nodes  
- Review API logs for affected accounts  
- Implement rate limiting and anomaly detection  
- Force password resets for any compromised accounts
