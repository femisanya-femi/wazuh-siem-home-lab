# Wazuh SIEM Home Lab

## Project Overview

This project documents the design, deployment, and operation of a Security Information and Event Management (SIEM) home lab using Wazuh. The lab was built in Oracle VirtualBox using Ubuntu Server as the SIEM server and Windows 10 as the monitored endpoint.

The objective of this project is to gain hands-on experience in SOC operations, endpoint monitoring, log analysis, threat detection, and incident investigation.

---

## Objectives

- Build a functional SIEM home lab
- Deploy Wazuh Server on Ubuntu Server
- Configure a Windows 10 endpoint
- Connect the Windows endpoint to the Wazuh Manager
- Monitor endpoint activity
- Analyze security events
- Perform incident investigations
- Document the entire deployment process

---

## Lab Environment

| Component | Details |
|-----------|---------|
| Host Machine | Windows 10 |
| Hypervisor | Oracle VirtualBox 7.2.8 |
| SIEM Platform | Wazuh 4.12 |
| Server OS | Ubuntu Server 24.04.4 LTS |
| Endpoint | Windows 10 |
| Network Mode | Bridged Adapter |

---

## Network Configuration

| Device | IP Address |
|---------|------------|
| Ubuntu Wazuh Server | 192.168.1.153 |
| Windows 10 Endpoint | 192.168.1.47 |

---

## Current Project Status

- [x] Ubuntu Server installed
- [x] Wazuh Server installed
- [x] Wazuh Dashboard operational
- [x] Windows Agent installed
- [x] Windows Agent enrolled
- [x] Endpoint communicating with Wazuh

---

## Skills Demonstrated

- Linux Administration
- Windows Administration
- Oracle VirtualBox
- Wazuh SIEM Deployment
- Endpoint Monitoring
- Network Configuration
- Service Troubleshooting
- Security Monitoring
- Technical Documentation

---

## Upcoming Work

- Install Sysmon
- Configure advanced log collection
- Investigate Windows Security Events
- Build custom detection rules
- Map detections to MITRE ATT&CK
- Perform threat hunting
- Document security incidents

---

## Repository Structure

```
wazuh-siem-home-lab
│
├── README.md
├── screenshots
├── diagrams
├── commands
├── incident-reports
└── docs
```

---

## Author

**Omosanya Femi (Bluegram)**

Aspiring SOC Analyst | Building practical cybersecurity projects through hands-on labs.
