# SentinelX SOC

> A Security Operations Center (SOC) laboratory for threat detection, alert triage, security investigation, incident response, MITRE ATT&CK mapping, and security automation.

## Project Overview

SentinelX SOC is a cybersecurity portfolio project designed to demonstrate an end-to-end SOC workflow in an isolated virtual laboratory.

The project focuses on collecting security telemetry, detecting suspicious activity, investigating alerts, mapping activity to MITRE ATT&CK techniques, assigning risk, and documenting incident response.

## Objectives

- Monitor Windows and Linux endpoints
- Collect endpoint and network security telemetry
- Develop and test security detections
- Perform alert triage and investigation
- Build investigation timelines
- Map detections to MITRE ATT&CK
- Perform controlled security scenarios
- Automate selected SOC tasks using Python
- Produce professional incident reports

## Technology Stack

| Technology | Purpose |
|---|---|
| Wazuh | Security monitoring |
| Sysmon | Windows endpoint telemetry |
| Wireshark | Network traffic analysis |
| Zeek | Network security monitoring |
| Python | SOC automation |
| Linux | SOC server |
| Windows | Endpoint monitoring |
| Kali Linux | Authorized security testing |
| MITRE ATT&CK | Threat technique mapping |
| GitHub | Source code and documentation |

## Core SOC Capabilities

### Security Monitoring

Collect and analyze security events from Windows, Linux, and network sources.

### Detection Engineering

Develop and test detections for suspicious authentication, endpoint, network, and process activity.

### Alert Triage

Classify alerts, investigate evidence, identify false positives, and determine severity.

### Threat Investigation

Build timelines and correlate events to understand suspicious activity.

### MITRE ATT&CK Mapping

Map relevant detections and investigation findings to MITRE ATT&CK techniques.

### Incident Response

Document the incident lifecycle:

Alert → Validation → Investigation → Scoping → Containment → Eradication → Recovery → Lessons Learned

### Security Automation

Python scripts will assist with:

- Log parsing
- Alert processing
- Risk scoring
- Timeline generation
- Security reporting

## Detection Catalogue

| ID | Detection |
|---|---|
| DET-001 | Repeated authentication failures |
| DET-002 | Successful login after repeated failures |
| DET-003 | Suspicious PowerShell activity |
| DET-004 | Unexpected administrator account change |
| DET-005 | Network reconnaissance |
| DET-006 | Unusual outbound connection |
| DET-007 | SSH authentication anomaly |
| DET-008 | Suspicious web request |
| DET-009 | Suspicious process activity |
| DET-010 | Multi-stage suspicious activity |

## Project Structure

```text
sentinelx-soc/
├── architecture/
├── detections/
├── incidents/
├── automation/
├── mitre/
├── dashboards/
├── screenshots/
├── reports/
├── docs/
└── README.md
