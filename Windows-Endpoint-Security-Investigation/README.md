# Windows Endpoint Security Investigation

**Project Type:** Simulated SOC Investigation  
**Role:** Tier-1 SOC Analyst  
**Platform:** Windows Endpoint  
**Focus:** Endpoint Detection, Process Analysis, Threat Detection, and Incident Response

---

## Incident Overview

A Windows workstation generated a security alert after a user executed a suspicious application.

The activity indicated potentially malicious process execution and abnormal behavior on the endpoint. The investigation focused on determining the nature of the activity, identifying indicators of compromise, and recommending appropriate response actions.

---

## Investigation Objectives

- Analyze suspicious endpoint activity
- Identify potentially malicious processes
- Review indicators of compromise
- Determine incident severity
- Assess potential security impact
- Recommend containment and remediation actions

---

## Initial Findings

The investigation identified suspicious process execution on the affected Windows workstation.

The process behavior was inconsistent with normal user activity and required further investigation to determine whether the endpoint had been compromised.

---

## Investigation Timeline

| Stage | Activity |
|---|---|
| 1 | Security alert generated |
| 2 | Suspicious process identified |
| 3 | Process behavior investigated |
| 4 | Potential IOC identified |
| 5 | Incident severity assessed |
| 6 | Containment and remediation recommended |

---

## Indicators of Compromise

- Suspicious executable
- Abnormal process execution
- Unexpected endpoint behavior
- Potential unauthorized system activity
- Unusual parent-child process relationship

---

## Severity Assessment

**Severity: Medium**

The activity presented a potential endpoint compromise risk. Further investigation was required to determine whether malicious code executed successfully and whether additional systems were affected.

---

## MITRE ATT&CK Mapping

| Technique | Description |
|---|---|
| T1059 | Command and Scripting Interpreter |
| T1204 | User Execution |
| T1105 | Ingress Tool Transfer |

---

## Analyst Assessment

The activity was assessed as suspicious and potentially malicious.

The combination of abnormal process execution and unexpected endpoint behavior justified escalation for further analysis.

No assumption of confirmed compromise was made without additional forensic evidence.

---

## Recommended Response

1. Isolate the affected endpoint if malicious activity is confirmed.
2. Investigate the suspicious executable and its origin.
3. Review Windows security and application logs.
4. Analyze related processes and network connections.
5. Identify additional affected systems or accounts.
6. Remove malicious files or persistence mechanisms.
7. Run endpoint security scans.
8. Reset affected credentials if compromise is confirmed.
9. Continue monitoring for related activity.
10. Document the investigation and final findings.

---

## Skills Demonstrated

- SOC alert triage
- Windows endpoint security
- Process analysis
- Threat detection
- IOC identification
- Incident severity assessment
- MITRE ATT&CK mapping
- Incident response
- Security documentation

---

## Disclaimer

This is a simulated cybersecurity investigation created for educational and professional portfolio purposes. No real organization's systems or data were involved.
