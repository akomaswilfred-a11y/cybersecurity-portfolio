# SIEM Log Analysis & Threat Detection

## Project Type
Simulated SOC Investigation

## Role
Tier-1 SOC Analyst

## Platform
Security Information and Event Management (SIEM)

## Focus
Log Analysis, Alert Investigation, Threat Detection, IOC Identification, and Incident Response

---

## Incident Overview

A SIEM platform generated multiple security alerts after detecting suspicious authentication activity across an organization's environment.

The investigation focused on identifying abnormal login behavior, determining whether the activity represented a potential account compromise, and documenting the appropriate SOC response.

---

## Investigation Objectives

- Analyze authentication and security logs
- Identify suspicious login patterns
- Investigate Indicators of Compromise (IOCs)
- Determine the severity of the activity
- Correlate multiple security events
- Recommend appropriate containment and response actions

---

## Initial Findings

The investigation identified several failed authentication attempts followed by a successful login from an unusual source.

The activity was inconsistent with the user's normal authentication behavior and was treated as potentially malicious.

---

## Indicators of Compromise

- Multiple failed login attempts
- Successful authentication following repeated failures
- Unusual source IP address
- Abnormal authentication timing
- Suspicious account activity

---

## Analyst Assessment

The activity was assessed as a potential credential compromise.

The combination of repeated authentication failures and a subsequent successful login from an unfamiliar source warranted further investigation and escalation.

---

## Recommended Response

1. Validate the user's identity and recent activity.
2. Review additional authentication logs.
3. Investigate the source IP address.
4. Revoke active sessions if compromise is confirmed.
5. Reset the affected account credentials.
6. Enable or enforce MFA.
7. Continue monitoring for related activity.
8. Document and escalate the incident according to SOC procedures.

---

## Skills Demonstrated

- SIEM monitoring
- Security log analysis
- Alert triage
- IOC identification
- Authentication investigation
- Incident severity assessment
- Incident response
- Security documentation
