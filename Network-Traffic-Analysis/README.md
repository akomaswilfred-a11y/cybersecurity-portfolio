# Network Traffic Analysis & Incident Detection

**Project Type:** Simulated SOC Investigation  
**Role:** Tier-1 SOC Analyst  
**Platform:** Network Monitoring Environment  
**Focus:** Network Traffic Analysis, IOC Identification, and Incident Response

## Incident Overview

A security monitoring system generated an alert after detecting unusual outbound network traffic from an internal workstation.

The workstation established repeated connections to an unfamiliar external IP address over a short period of time. The activity was inconsistent with the user's normal network behavior.

## Initial Findings

- Source host: Internal employee workstation
- Destination: Unfamiliar external IP address
- Protocol: TCP
- Destination port: 443
- Connection pattern: Repeated outbound connections
- User activity: No known business requirement for the destination
- Traffic volume: Higher than the workstation's normal baseline
- Alert type: Suspicious outbound network activity

## Investigation

The investigation focused on determining whether the traffic represented normal application behavior, unauthorized communication, or possible malware activity.

The analyst reviewed the source host, destination address, connection frequency, destination port, and timing of the network activity.

The repeated connections to an unfamiliar external system increased the likelihood of a potentially compromised endpoint.

## Indicators of Compromise (IOCs)

- Suspicious external IP address
- Repeated outbound connections
- Unusual connection frequency
- Unexpected communication from the affected workstation

## Analyst Assessment

The activity was classified as **Suspicious Network Activity** requiring further investigation.

The available evidence was insufficient to confirm malware infection, but the traffic pattern justified escalation to a higher-level security analyst.

## Recommended Response

1. Isolate the affected workstation from the network if suspicious activity continues.
2. Investigate running processes and recently installed applications.
3. Review endpoint security alerts and system logs.
4. Check the destination IP against threat intelligence sources.
5. Search for the same IP address across other organizational endpoints.
6. Block the destination if confirmed malicious.
7. Document the investigation and escalate if additional indicators of compromise are discovered.

## Conclusion

This simulated investigation demonstrates a Tier-1 SOC analyst's ability to identify unusual network behavior, analyze basic network indicators, recognize potential indicators of compromise, and recommend appropriate incident response actions.
