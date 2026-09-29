# Phase 4 – Project Planning

## Project Title
Standard Laptop Procurement Automation

## Project Goal

To automate the Standard Laptop procurement process in
ServiceNow using Flow Designer.

## Project Tasks

| Task | Description |
|---|---|
| 1 | Create the Flow in Flow Designer |
| 2 | Configure Flow properties |
| 3 | Add Service Catalog trigger |
| 4 | Add Create Catalog Task action |
| 5 | Map Requested Item Record |
| 6 | Configure Short Description |
| 7 | Configure Description |
| 8 | Set Assignment Group as Hardware |
| 9 | Set Approval as Approved |
| 10 | Save and Activate the Flow |
| 11 | Add the Flow to Standard Laptop Process Engine |
| 12 | Test the Standard Laptop request |
| 13 | Verify the generated Catalog Task |

## Flow Configuration Plan

### Flow Name
Standard Laptop Task

### Application
Global

### Run As
System User

### Trigger
Service Catalog

### Action
Create Catalog Task

## Task Configuration

- Short Description: Laptop need to Configured
- Description: Laptop need to Configured
- Assignment Group: Hardware
- Approval: Approved

## Testing Plan

1. Open Service Catalog.
2. Select Hardware.
3. Select Standard Laptop.
4. Click Order Now.
5. Open the created Request.
6. Open the Requested Item.
7. Approve the request.
8. Check the Catalog Tasks section.
9. Open the created Catalog Task.
10. Verify the short description.
11. Verify the assignment group.
12. Verify the approval value.

## Expected Result

After the Standard Laptop request is approved, the Flow should
automatically create a Catalog Task and assign it to the
Hardware assignment group.

## Project Outcome

The planned automation reduces manual task creation and ensures
that approved Standard Laptop requests are consistently assigned
to the Hardware team.
