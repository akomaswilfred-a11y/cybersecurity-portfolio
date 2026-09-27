# Microsoft 365 Account Compromise Investigation

**Project Type:** Simulated SOC Investigation  
**Role:** Tier-1 SOC Analyst  
**Platform:** Microsoft 365

## Incident Overview

A Microsoft 365 account generated an alert after 14 failed login attempts were followed by a successful login from an unusual geographic location.

## Initial Findings

- Normal location: United Kingdom
- Suspicious location: Nigeria
- Login time: 03:17 AM
- Device: Unrecognized
- MFA: Not completed
- Failed attempts: 14

The activity was inconsistent with the user's established login pattern.

## Investigation

The user's previous 30 days of authentication activity were reviewed to establish a baseline.

Previous successful logins originated from the UK, with no travel notification.

Post-authentication activity was then reviewed.

## Indicators of Compromise

The audit logs showed:

- A new email forwarding rule was created.
- 37 emails were accessed.
- A suspicious OAuth application was granted mailbox permissions.

These findings indicated likely unauthorized access.

## Severity Assessment

**HIGH**

The incident was classified as high severity because an unauthorized actor appeared to have gained access to the account and performed suspicious actions within the mailbox.

## Containment Actions

1. Escalate to Incident Response / Tier 2.
2. Restrict or disable the compromised account according to the response playbook.
3. Force a password reset.
4. Revoke active sessions and authentication tokens.
5. Remove the unauthorized forwarding rule.
6. Revoke the suspicious OAuth application's permissions.

## Further Investigation

The SOC should determine:

- Whether sensitive information was accessed or exfiltrated.
- Whether other accounts were targeted.
- Whether the suspicious IP appeared elsewhere.
- Whether additional malicious forwarding rules or OAuth applications exist.

## Skills Demonstrated

- Security alert investigation
- Authentication-log analysis
- User behavior analysis
- Account compromise detection
- Incident severity assessment
- Incident escalation
- Containment planning
- Microsoft 365 security concepts

> **Note:** This is a simulated investigation created for cybersecurity training and portfolio demonstration. No real user account or production environment was accessed.
