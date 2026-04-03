## Title
Kerberos Ticket Abuse

## Time
2026-03-24 03:27:19 UTC

## Summary
Suspicious TGT requests by `svc-db` with lifetime extended beyond policy, indicating potential golden ticket usage.

## Analysis
Unauthorized Kerberos ticket manipulation indicates privilege abuse and potential domain-wide compromise.

## Classification
- Incident Type: Privilege Abuse / Kerberos Ticket  
- Severity: Critical  
- Confidence Level: High  
- Disposition: True Positive  

## Recommendation Action
- Investigate `svc-db` account and host  
- Reset credentials and Kerberos tickets  
- Monitor for further abnormal TGT requests  
- Review domain security policies
