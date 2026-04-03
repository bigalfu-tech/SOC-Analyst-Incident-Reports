## Title
Privilege Escalation Detected

## Time
2026-03-17 12:08:56 UTC

## Summary
User `j.smith` added to Domain Admins by `svc-backup` account without change ticket.

## Analysis
Unauthorized privilege escalation increases risk of full domain compromise. Lack of ticket indicates potential policy violation or attack.

## Classification
- Incident Type: Privilege Escalation  
- Severity: Critical  
- Confidence Level: High  
- Disposition: True Positive  

## Recommendation Action
- Remove unauthorized privileges  
- Investigate `svc-backup` account activity  
- Enforce privileged account approval workflow  
- Monitor for lateral movement
