# Step 02 - Enable Microsoft Sentinel

## Overview

Microsoft Sentinel is enabled on top of the Log Analytics Workspace created in Step 01.

## Steps

1. In the Azure portal, search **Microsoft Sentinel**
2. Click **Create**
3. Select the workspace created in Step 01 (`sc200-lab-workspace`)
4. Click **Add**
5. Wait for provisioning to complete (usually 1-2 minutes)

## Post-Setup

Once enabled, the Sentinel overview blade will show:
- Incidents
- Alerts
- Data connectors status
- Active analytics rules

## Screenshots

> *(Add screenshots here)*

## Notes

- The 90-day free trial starts the moment you enable Sentinel on the workspace
- After the trial, ingestion is billed per GB — keep data sources minimal to control cost
