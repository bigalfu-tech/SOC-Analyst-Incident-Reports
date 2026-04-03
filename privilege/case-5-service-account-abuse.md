## Title
Service Account Abuse

## Time
2026-03-31 06:52:13 UTC

## Summary
`svc-payroll` logged in interactively from CEO laptop, unusual for service accounts.

## Analysis
Interactive login by a service account indicates potential misuse or compromise. Behavior deviates from expected operational patterns.

## Classification
- Incident Type: Privilege Abuse / Service Account Misuse  
- Severity: High  
- Confidence Level: High  
- Disposition: True Positive  

## Recommendation Action
- Restrict service account to non-interactive logins  
- Investigate host and account activity  
- Monitor for further anomalies  
- Review service account policies
