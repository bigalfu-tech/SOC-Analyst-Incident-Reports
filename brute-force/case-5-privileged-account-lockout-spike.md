## Title
Privileged Account Lockout Spike

## Time
2026-03-31 22:58:11 UTC

## Summary
Nine domain admin accounts locked within 3 minutes from host WS-IT-224. Kerberos pre-auth failures detected, followed by SMB connection attempts.

## Analysis
Rapid lockouts of multiple privileged accounts indicate a targeted brute force attack. Subsequent SMB activity suggests lateral movement attempts.

## Classification
- Incident Type: Brute Force / Privileged Account Attack  
- Severity: Critical  
- Confidence Level: High  
- Disposition: True Positive  

## Recommendation Action
- Unlock accounts and reset passwords  
- Enable MFA for all domain admins  
- Investigate WS-IT-224 host  
- Monitor SMB traffic for lateral movement
