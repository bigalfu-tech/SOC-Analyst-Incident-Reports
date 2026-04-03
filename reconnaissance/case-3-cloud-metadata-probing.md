## Title
Cloud Metadata Probing

## Time
2026-03-23 09:17:55 UTC

## Summary
Requests to 169.254.169.254 originated from container payments-api-prod-3 attempting to retrieve IAM credentials. Behavior is unusual for the application.

## Analysis
Unauthorized metadata access attempts indicate potential cloud privilege escalation or credential harvesting within containerized environments.

## Classification
- Incident Type: Reconnaissance / Cloud Metadata Access  
- Severity: High  
- Confidence Level: High  
- Disposition: True Positive  

## Recommendation Action
- Isolate container  
- Rotate IAM credentials if any exposure  
- Review container deployment and permissions  
- Monitor for further metadata access attempts
