# Standard Laptop Task – ServiceNow

## Project Overview

This project demonstrates a **ServiceNow Service Catalog / Workflow Studio** configuration for a **Standard Laptop Task**.

The workflow is designed to create a **Catalog Task** when the Service Catalog process is triggered.

## Platform

- **Platform:** ServiceNow
- **Module / Area:** Service Catalog and Workflow Studio
- **Flow Name:** Standard laptop task
- **Action:** Create Catalog Task
- **Catalog Task Table:** `sc_task`

## Workflow Configuration

The implemented flow contains the following configuration:

1. **Trigger:** Service Catalog
2. **Input:** Requested Item Record
3. **Action:** Create Catalog Task
4. **Short Description:** `Laptop need to Configured`
5. **Description:** `Laptop need to Configured`
6. **Assignment Group:** `Hardware`
7. **Approval:** `Approved`

## Result

The workflow successfully created a Catalog Task record.

### Sample Catalog Task

- **Task Number:** `SCTASK0010001`
- **Approval:** Approved
- **Priority:** 4 - Low
- **State:** Open
- **Request Item:** `RITM0010001`
- **Requested For:** System Administrator
- **Short Description:** `Laptop need to Configured`

## Project Evidence

Screenshots are included in the `screenshots` folder:

| File | Description |
|---|---|
| `01-servicenow-project-environment.png` | ServiceNow project environment |
| `02-workflow-standard-laptop-task.png` | Workflow Studio configuration for the Standard laptop task flow |
| `03-created-catalog-task-record.png` | Created Catalog Task record and its field values |

## Key Learning

This project demonstrates how ServiceNow can be configured to automate the creation of Catalog Tasks from a Service Catalog trigger using Workflow Studio.

## Notes

This repository contains project documentation and screenshots as implementation evidence. No separate programming source code is required for this configuration-based ServiceNow project.
