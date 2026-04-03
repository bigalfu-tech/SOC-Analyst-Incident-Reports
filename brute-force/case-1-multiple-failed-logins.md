
## Title
Multiple Failed Login Attempts – Brute Force Attack

## Time
2026-03-18 02:14:33 UTC

## Summary
User `corp_j.dawson` experienced 187 failed login attempts over 9 minutes targeting the VPN gateway. The final attempt succeeded.

## Analysis
The login attempts originated from IP 185.193.88.41 (Russia ASN) and followed a sequential dictionary password pattern. The high volume and eventual success indicate a brute force attack with probable account compromise.

## Classification
- Incident Type: Brute Force Attack  
- Severity: High  
- Confidence Level: High  
- Disposition: True Positive  

## Recommendation Action
- Force password reset for the affected user  
- Enable MFA on the VPN account  
- Block or monitor the source IP  
- Review VPN logs for suspicious activity
