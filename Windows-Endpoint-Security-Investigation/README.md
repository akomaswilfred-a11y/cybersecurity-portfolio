# Windows Endpoint Security Investigation

**Project Type:** Simulated SOC Investigation  

**Role:** Tier-1 SOC Analyst  

**Platform:** Windows Endpoint  

**Focus:** Endpoint Detection, Process Analysis and Incident Response

## Incident Overview

A Windows workstation generated a security alert after a user executed a suspicious application downloaded from an external source.

The alert indicated unusual process activity followed by an outbound network connection to an unfamiliar external IP address.

## Initial Findings

- User executed an unknown executable from the Downloads folder.

- The executable launched an unusual child process.

- The process attempted an outbound connection to an unfamiliar IP address.

- The activity occurred outside the user's normal software usage pattern.

- The file was not recognized as an approved business application.

## Investigation

The endpoint activity was reviewed to determine whether the process execution was legitimate or potentially malicious.

The investigation focused on:

- Process execution and parent-child relationships

- File location and execution path

- Network connections initiated by the process

- User activity surrounding the alert

- Persistence indicators

- Similar activity on other endpoints

## Indicators of Suspicious Activity

The following behaviors increased the risk assessment:

- Execution of an unknown executable

- Unusual child-process creation

- External network communication

- Execution from a user-writable directory

- Activity inconsistent with normal user behavior

## Severity Assessment

**MEDIUM-HIGH**

The activity presented indicators consistent with potentially malicious endpoint behavior and required further investigation.

## Recommended Response

1. Isolate the affected endpoint from the network.

2. Escalate the alert to Incident Response / Tier 2.

3. Preserve relevant endpoint and security logs.

4. Identify and analyze the suspicious executable.

5. Review related network connections.

6. Search for the same file or indicators across other endpoints.

7. Remove malicious artifacts if confirmed.

8. Restore the endpoint after validation and remediation.

## Further Investigation

The SOC should determine:

- Whether the executable was malicious.

- Whether additional processes were created.

- Whether persistence mechanisms were established.

- Whether credentials were accessed.

- Whether other endpoints contacted the same destination.

- Whether any data was accessed or exfiltrated.

## Skills Demonstrated

- Endpoint alert investigation

- Process analysis

- Windows security concepts

- Network connection analysis

- Threat detection

- Incident severity assessment

- Incident escalation

- Endpoint containment

- SOC investigation methodology

> **Note:** This is a simulated investigation created for
