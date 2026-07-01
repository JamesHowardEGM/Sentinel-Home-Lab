# KQL Detection Queries

Custom KQL queries written and tested in this Sentinel lab.

## Query Library

| Query | Table | Description |
|---|---|---|
| [Failed Sign-ins](failed-sign-ins.kql) | SigninLogs | Detects multiple failed Azure AD sign-in attempts |
| *(more added as lab progresses)* | | |

## Query Format

Each query file includes:
- The KQL query itself
- Description of what it detects
- MITRE ATT&CK technique mapping
- Notes on tuning thresholds
