# Home SOC Lab

## Overview

This project simulates a small-scale Security Operations Center (SOC) environment to collect logs, detect suspicious activity, and perform basic incident investigations.

The lab is built using virtual machines and a centralized SIEM platform to replicate real-world security monitoring workflows.

---

## Objective

* Build a working SOC lab environment
* Collect and centralize logs from multiple systems
* Investigate suspicious activity using log data
* Create basic detection rules
* Document findings and security concepts

---

## Lab Architecture

* Platform: VMware Workstation Pro
* Monitoring Server: Ubuntu Server (Wazuh)
* Endpoint 1: Windows 11 (Sysmon)
* Endpoint 2: Ubuntu Desktop 

> Architecture diagram will be added in Week 2

---

## Tools & Technologies

* Wazuh (SIEM and log analysis)
* Sysmon (Windows system monitoring)
* Ubuntu Server (log collection and analysis)
* Windows 11 (endpoint telemetry)
* VMware Workstation Pro (virtualization)

---

## Implementation (Week 1–4 Roadmap)

### Week 1 – Setup

* Created virtual lab environment
* Installed Ubuntu Server and Windows VM

### Week 2 – Build the Lab

* Install Wazuh server
* Connect Ubuntu and Windows agents
* Install Sysmon on Windows
* Verify log ingestion

### Week 3 – Generate Activity & Investigate

* Simulate events:

  * failed logins
  * PowerShell activity
  * file modifications
* Analyze logs and identify suspicious behavior

### Week 4 – Detection & Reporting

* Create detection rules
* Develop alerts for:

  * repeated failed logins
  * suspicious PowerShell usage
  * persistence techniques
* Write a mock incident report

---

## Key Concepts Learned

* SIEM fundamentals
* Log collection and analysis
* Windows Event Logs
* Endpoint telemetry
* Detection engineering basics
* Incident investigation workflow

---

## Example Use Cases

* Detecting brute-force login attempts
* Identifying suspicious PowerShell execution
* Monitoring account creation and persistence mechanisms

---

## Screenshots

*(To be added in Week 2–4)*

* Wazuh dashboard
* Log events
* Detection alerts

---

## Results

*(To be updated as the lab progresses)*

* Successful log ingestion from endpoints
* Identification of suspicious activities
* Creation of detection rules

---

## Future Improvements

* Add additional endpoints (e.g., Kali Linux)
* Improve detection rules and alert tuning
* Integrate threat intelligence sources
* Expand automation and reporting

---

## Status

Week 1 – Infrastructure setup complete
Week 2 – Setup Wazuh on Ubuntu Server.

---
