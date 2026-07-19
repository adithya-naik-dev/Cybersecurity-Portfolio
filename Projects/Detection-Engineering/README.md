# Detection Engineering

## Overview

Detection Engineering is the process of designing, building, testing, and continuously improving security detections that identify malicious activity before it impacts an environment.

Instead of relying only on default security rules, detection engineers create custom detections based on attacker behaviour, threat intelligence, and organisational requirements to improve visibility and reduce false positives.

This section documents my hands-on learning and practical exercises completed while studying Detection Engineering through TryHackMe, where I explored detection strategies, Sigma rules, threat intelligence integration, and endpoint detection technologies.

---

## Learning Objectives

Throughout this module I learned how to:

- Understand the Detection Engineering lifecycle
- Build detections using attacker behaviour instead of only Indicators of Compromise (IOCs)
- Apply Threat Intelligence to improve security monitoring
- Write and customise Sigma rules
- Convert Sigma rules for different SIEM platforms
- Develop detection logic for Windows event logs
- Understand Detection as Code (DaC)
- Work with Sigma-based endpoint detection using Aurora EDR
- Improve detection quality through tuning and validation

---

## Key Concepts

### Detection Types

- Configuration Detection
- Behaviour-Based Detection
- Indicator-Based Detection (IOC)
- Threat Behaviour Detection (TTP)

Rather than depending on a single detection method, combining multiple approaches creates stronger and more reliable detections.

---

### Detection Lifecycle

A typical detection engineering workflow includes:

1. Detection Gap Analysis
2. Threat Modelling
3. Data Source Identification
4. Log Collection
5. Baseline Creation
6. Rule Development
7. Validation & Testing
8. Deployment
9. Continuous Tuning

Detection engineering is an ongoing process that evolves as attackers, environments, and technologies change.

---

### Detection as Code (DaC)

Detection as Code applies software engineering practices to security detections.

Benefits include:

- Version control
- Reusable detection logic
- Automated testing
- CI/CD integration
- Team collaboration
- Easier maintenance

---

### Detection Frameworks

This module introduced several frameworks commonly used by detection engineers:

- MITRE ATT&CK
- Cyber Analytics Repository (CAR)
- Pyramid of Pain
- Cyber Kill Chain
- Unified Kill Chain
- Palantir Alerting & Detection Strategy (ADS)
- Detection Maturity Level (DML)

These frameworks help map adversary behaviour, identify detection gaps, prioritise alerts, and improve investigation workflows.

---

## Tools & Technologies

- Sigma
- Aurora EDR
- Windows Event Logs
- Sysmon
- Event Tracing for Windows (ETW)
- Elastic Stack
- Splunk
- Kibana
- Uncoder.io
- Sigmac / Sigma CLI

---

## Projects

| Project | Description |
|---------|-------------|
| Intro to Detection Engineering | Detection lifecycle, detection methodologies, Detection as Code, and industry frameworks. |
| Tactical Detection | Building practical detections using IOCs, tripwires, Sigma rules, and purple-team techniques. |
| Threat Intelligence for SOC | Integrating IOC-based threat intelligence into prevention, detection, and SIEM workflows. |
| Sigma | Writing, converting, and validating Sigma detection rules across multiple SIEM platforms. |
| SigHunt | Creating Sigma rules from incident response findings and attacker IOCs. |
| Aurora EDR | Investigating Windows events using Aurora's Sigma-based endpoint detection capabilities. |

---

## Skills Demonstrated

- Detection Engineering
- Security Monitoring
- Detection Rule Development
- Sigma Rule Creation
- Threat Intelligence Integration
- Detection Validation
- Event Log Analysis
- Windows Security Monitoring
- Endpoint Detection & Response (EDR)
- SIEM Detection Development

---

## References

- TryHackMe Detection Engineering Module
- Sigma Project Documentation
- MITRE ATT&CK Framework
- CAR (Cyber Analytics Repository)
- Palantir ADS Framework
