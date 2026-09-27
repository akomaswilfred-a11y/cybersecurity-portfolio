# Identity & Access Management Investigation

**Project Type:** Simulated SOC Investigation  
**Role:** Tier-1 SOC Analyst  
**Platform:** Identity and Access Management Environment  
**Focus:** Authentication Analysis, Account Compromise Detection, and Incident Response

## Incident Overview

A security monitoring system generated an alert after detecting unusual authentication activity associated with a user account.

The account recorded multiple failed login attempts followed by a successful login from an unfamiliar geographic location and IP address.

The activity was considered suspicious because the successful authentication occurred shortly after repeated failed attempts.

## Initial Findings

- Multiple failed authentication attempts were observed against the same user account.
- A successful login occurred shortly after the failed attempts.
- The successful login originated from an unfamiliar external IP address.
- The login location was inconsistent with the user's normal activity.
- The authentication pattern suggested a possible credential compromise or brute-force attempt.

## Investigation

The authentication events were reviewed to establish a timeline and determine whether the activity represented legitimate user behavior.

The investigation focused on:

- Login timestamps
- Source IP addresses
- Geographic locations
- Failed and successful authentication attempts
- User account activity
- Authentication patterns

The sequence of repeated failures followed by a successful login increased the likelihood of unauthorized account access.

## Indicators of Compromise

| Indicator | Observation |
|---|---|
| Authentication failures | Multiple attempts |
| Successful login | Occurred after failed attempts |
| Source IP | Unfamiliar external address |
| Location | Inconsistent with normal activity |
| Account behavior | Abnormal authentication pattern |

## Analyst Assessment

The activity was assessed as **suspicious and potentially consistent with an account compromise attempt**.

The successful authentication following repeated failed attempts requires further investigation and validation with the legitimate user.

## Recommended Response

1. Temporarily suspend or protect the affected account.
2. Force a password reset.
3. Revoke active sessions and authentication tokens.
4. Enable or verify multi-factor authentication.
5. Review additional authentication activity associated with the account.
6. Investigate the source IP address for related activity.
7. Monitor the account for further suspicious authentication attempts.

## Conclusion

The investigation identified an abnormal authentication pattern involving repeated failed login attempts followed by a successful login from an unfamiliar location.

The incident demonstrates a Tier-1 SOC analyst's ability to analyze authentication events, identify indicators of potential account compromise, assess risk, and recommend appropriate containment actions.
