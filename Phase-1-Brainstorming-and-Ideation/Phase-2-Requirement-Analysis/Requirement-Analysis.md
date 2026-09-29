# Phase 2 – Requirement Analysis

## Project Title
Standard Laptop Procurement Automation

## Functional Requirements

1. The user should be able to submit a Standard Laptop request
   through the Service Catalog.

2. The request should go through the required approval process.

3. The Flow should be triggered for the Service Catalog request.

4. After the request is approved, the Flow should create a
   Catalog Task.

5. The Requested Item Record should be used while creating
   the Catalog Task.

6. The Catalog Task short description should be:
   "Laptop need to Configured"

7. The Catalog Task description should be:
   "Laptop need to Configured"

8. The Assignment Group should be:
   "Hardware"

9. The Approval value should be:
   "Approved"

10. The created Catalog Task should be visible under the
    Requested Item record.

## Non-Functional Requirements

- The automation should reduce manual work.
- The Flow should execute consistently.
- The task should be assigned to the correct group.
- The process should be easy to monitor in ServiceNow.

## Input

- Standard Laptop Service Catalog request
- Requested Item Record
- Approval status

## Process

Service Catalog Request
        ↓
Approval
        ↓
Flow Designer
        ↓
Create Catalog Task
        ↓
Assign to Hardware

## Output

A Catalog Task is automatically created with:

- Short Description: Laptop need to Configured
- Description: Laptop need to Configured
- Assignment Group: Hardware
- Approval: Approved

## Tools and Technologies

- ServiceNow
- Service Catalog
- Flow Designer
- Catalog Task
