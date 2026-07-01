# Microsoft Sentinel Home Lab

A hands-on Microsoft Sentinel home lab built for SC-200 exam preparation and practical security operations skill development.

## About

This lab simulates a real SOC environment using Microsoft Sentinel, the Microsoft Defender suite, and Azure infrastructure. It documents the full build process, custom KQL detection queries, threat intelligence configuration, and incident investigation walkthroughs.

Built by a cybersecurity student with hands-on SOC experience, working toward the SC-200: Microsoft Security Operations Analyst certification.

---

## Lab Architecture

| Component | Purpose |
|---|---|
| Azure Resource Group | Logical container for all lab resources |
| Log Analytics Workspace | Central log store for Sentinel |
| Microsoft Sentinel | SIEM / SOAR platform |
| Windows Server VM | Generates real security telemetry |
| Microsoft Entra ID | Identity and sign-in log source |
| Threat Intelligence Feed | Ingested via TAXII/STIX connector |
| Microsoft Defender for Cloud | Cloud security posture + alerts |

---

## Repository Structure

```
├── setup/              # Step-by-step lab build guides with screenshots
├── kql-queries/        # Custom KQL detection queries
├── playbooks/          # Logic App playbooks and automation rules
├── threat-intel/       # Threat intelligence feed configuration
├── investigations/     # Simulated incident investigation walkthroughs
└── screenshots/        # Lab screenshots and evidence
```

---

## Setup Guides

| Step | Guide |
|---|---|
| 01 | [Resource Group & Log Analytics Workspace](setup/01-resource-group-and-workspace.md) |
| 02 | [Enable Microsoft Sentinel](setup/02-enable-sentinel.md) |
| 03 | [Deploy Windows VM](setup/03-deploy-windows-vm.md) |
| 04 | [Configure Data Connectors](setup/04-data-connectors.md) |
| 05 | [Ingest Threat Intelligence](setup/05-threat-intelligence.md) |
| 06 | [Create Analytics Rules](setup/06-analytics-rules.md) |
| 07 | [Build Automation Playbook](setup/07-playbooks.md) |

---

## KQL Queries

Custom detection queries written and tested in this lab. See [kql-queries/](kql-queries/) for full library.

---

## Certifications Being Worked Toward

- SC-200: Microsoft Security Operations Analyst
- AZ-104: Microsoft Azure Administrator
- AZ-500: Microsoft Azure Security Engineer

---

## Background

- Bachelor of Cybersecurity (graduating 2026, WAM: 80)
- eJPT certified
- 12-week SOC internship (Microsoft Sentinel environment)
- 12-week IT Services internship (in progress)
- Cert II Security Operations (in progress)
