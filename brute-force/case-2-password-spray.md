## Title
Password Spray Detected – Brute Force Attack

## Time
2026-03-21 11:02:10 UTC

## Summary
63 usernames were targeted with the password `Winter@2026`. Four service accounts were successfully compromised from IP 45.77.210.19, with logins from Vietnam while users are based in the UK.

## Analysis
Repeated use of a common password across multiple accounts indicates a password spray attack. Successful logins and geo-mismatched access increase the likelihood of unauthorized activity.

## Classification
- Incident Type: Password Spray Attack  
- Severity: High  
- Confidence Level: High  
- Disposition: True Positive  

## Recommendation Action
- Reset passwords for compromised accounts  
- Enforce MFA for service accounts  
- Block source IP and monitor for further login attempts  
- Investigate any misuse of compromised accounts
