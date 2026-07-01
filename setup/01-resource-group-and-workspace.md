# Step 01 - Resource Group & Log Analytics Workspace

## Overview

All lab resources are contained within a single Azure Resource Group. The Log Analytics Workspace is the foundation that Microsoft Sentinel sits on top of — all ingested data flows into it.

## Steps

### 1. Create Resource Group

1. In the Azure portal search bar, search **Resource groups**
2. Click **Create**
3. Set the following:
   - **Subscription:** Your free tier subscription
   - **Resource group name:** `SC200-Lab`
   - **Region:** Australia East
4. Click **Review + Create** → **Create**

### 2. Create Log Analytics Workspace

1. Search **Log Analytics workspaces** in the portal
2. Click **Create**
3. Set the following:
   - **Resource group:** `SC200-Lab`
   - **Name:** `sc200-lab-workspace`
   - **Region:** Australia East
4. Click **Review + Create** → **Create**

## Screenshots

> *(Add screenshots here)*

## Notes

- Keep everything in the same region to avoid data transfer costs
- The workspace name must be globally unique — add your initials if needed
