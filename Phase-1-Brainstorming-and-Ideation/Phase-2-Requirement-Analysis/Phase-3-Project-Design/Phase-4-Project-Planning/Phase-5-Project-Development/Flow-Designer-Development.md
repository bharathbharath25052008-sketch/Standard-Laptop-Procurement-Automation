# Phase 5 – Project Development

## Project Title

Standard Laptop Procurement Automation

## Platform

ServiceNow

## Module

Flow Designer

## Flow Name

Standard Laptop Task

## Flow Configuration

### Application
Global

### Run As
System User

## Trigger Configuration

The Flow is triggered using the Service Catalog trigger.

### Trigger
Service Catalog

## Action Configuration

### Action
Create Catalog Task

### Request Item
Requested Item Record

### Table
Catalog Task

## Catalog Task Field Values

| Field | Value |
|---|---|
| Short Description | Laptop need to Configured |
| Description | Laptop need to Configured |
| Assignment Group | Hardware |
| Approval | Approved |

## Flow Process

1. Create a new Flow in Flow Designer.
2. Set the Flow name as Standard Laptop Task.
3. Select Global as the Application.
4. Select System User under Run As.
5. Add the Service Catalog trigger.
6. Add the Create Catalog Task action.
7. Select the Requested Item Record.
8. Set the Short Description.
9. Set the Description.
10. Set the Assignment Group as Hardware.
11. Set Approval as Approved.
12. Save the Flow.
13. Activate the Flow.

## Service Catalog Configuration

The Standard Laptop catalog item is configured to use the
created Flow through its Process Engine configuration.

## Development Result

The Flow is successfully configured to create a Catalog Task
after the Standard Laptop request is approved.

The generated task contains the required description and is
assigned to the Hardware assignment group.

## Screenshots

Screenshots of the ServiceNow configuration and Flow execution
will be added to this phase as project evidence.
