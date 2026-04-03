## Title
OAuth Consent Grant – Suspicious Application

## Time
2026-03-22 13:27:14 UTC

## Summary
User `hr.manager@company.com` granted OAuth permissions to unverified app `DocuShare Pro` from an IP in Nigeria.

## Analysis
Unauthorized OAuth app permissions can provide access to mail and files. IP geolocation mismatch and unverified application indicate potential credential harvesting.

## Classification
- Incident Type: Phishing / Malicious App Consent  
- Severity: High  
- Confidence Level: High  
- Disposition: True Positive  

## Recommendation Action
- Revoke app permissions immediately  
- Reset user credentials  
- Educate user on approving only verified apps  
- Monitor mailbox activity for suspicious access
