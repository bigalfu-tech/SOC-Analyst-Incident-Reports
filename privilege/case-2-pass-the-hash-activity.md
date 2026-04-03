## Title
Pass-the-Hash Activity

## Time
2026-03-20 19:44:03 UTC

## Summary
NTLM authentication observed across 8 servers with multiple lateral logins from WS-OPS-12.

## Analysis
Pattern indicates pass-the-hash attack; high risk of lateral movement and domain compromise.

## Classification
- Incident Type: Privilege Abuse / Pass-the-Hash  
- Severity: Critical  
- Confidence Level: High  
- Disposition: True Positive  

## Recommendation Action
- Disable affected accounts and reset credentials  
- Investigate host for compromise  
- Monitor lateral authentication attempts  
- Apply patches and security hardening
