# Phishing Email Investigation

**Project Type:** Simulated SOC Investigation  
**Role:** Tier-1 SOC Analyst  
**Focus:** Phishing Detection and Email Security

## Incident Overview

An employee reported a suspicious email requesting them to verify their Microsoft 365 account through an unfamiliar link.

The email appeared to imitate a legitimate Microsoft security notification.

## Initial Findings

- Sender address: suspicious external domain
- Display name: Microsoft Security
- Recipient: Employee mailbox
- Subject: Urgent Account Verification Required
- Message contained a credential-harvesting link
- Email used urgency to pressure the recipient
- Sender domain did not match Microsoft's legitimate domains
- User had not requested an account verification

## Indicators of Phishing

The following characteristics indicated a likely phishing attempt:

1. Suspicious sender domain
2. Impersonation of a trusted organization
3. Urgent language
4. Credential-harvesting link
5. Unexpected account verification request

## Investigation

The email was analyzed using the available message details and reported indicators.

The sender domain was compared against the expected legitimate domain.

The embedded link was identified as the primary risk because it could redirect the user to a fraudulent login page designed to capture credentials.

No evidence was found that the user intentionally requested the verification.

## Severity Assessment

**MEDIUM-HIGH**

The email presented a significant credential-theft risk. If the user submitted credentials, the account could potentially be compromised.

## Recommended Response

1. Remove or quarantine the malicious email.
2. Block the identified sender/domain.
3. Block the malicious URL through available security controls.
4. Confirm whether the recipient clicked the link.
5. If credentials were submitted, force a password reset.
6. Revoke active sessions and authentication tokens if compromise is suspected.
7. Review authentication logs for suspicious activity.
8. Search for similar messages sent to other employees.

## Further Investigation

The SOC should determine:

- Whether the user clicked the link.
- Whether credentials were submitted.
- Whether other employees received the same email.
- Whether the sender domain appears in other security alerts.
- Whether authentication anomalies occurred after the email was received.

## Skills Demonstrated

- Phishing detection
- Email security analysis
- Social engineering identification
- IOC identification
- Incident severity assessment
- Security response planning
- Account compromise prevention
- SOC investigation

> **Note:** This is a simulated investigation created for cybersecurity training and portfolio demonstration. No real phishing campaign or production environment was accessed.
