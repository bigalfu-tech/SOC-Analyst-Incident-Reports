## Title
LDAP Query Spike

## Time
2026-03-26 16:41:20 UTC

## Summary
User `temp.contractor` performed 12,000 LDAP queries in 10 minutes querying attributes `memberOf` and `adminCount`. Tool fingerprint: BloodHound.

## Analysis
High-volume LDAP queries are indicative of reconnaissance to map domain privileges and structure. BloodHound fingerprint confirms malicious intent.

## Classification
- Incident Type: Reconnaissance / LDAP Mapping  
- Severity: High  
- Confidence Level: High  
- Disposition: True Positive  

## Recommendation Action
- Suspend the user account temporarily  
- Investigate host for compromise  
- Review LDAP query logs  
- Enforce least privilege and MFA
