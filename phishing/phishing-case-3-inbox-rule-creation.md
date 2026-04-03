## Title
Inbox Rule Creation – Potential Phishing

## Time
2026-03-24 08:11:02 UTC

## Summary
User `accounts.payable@company.com` created an inbox rule moving “invoice” emails to RSS folder from an IP in Poland (geo mismatch).

## Analysis
Unauthorized mailbox rules can divert important emails for fraudulent purposes. Geo-mismatch indicates account compromise.

## Classification
- Incident Type: Phishing / Mailbox Compromise  
- Severity: High  
- Confidence Level: High  
- Disposition: True Positive  

## Recommendation Action
- Remove unauthorized inbox rule  
- Reset user credentials and enforce MFA  
- Review email logs for forwarded/missing messages  
- Educate user about suspicious rule creation
