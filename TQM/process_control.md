# Process Control

## Room Allocation Control

```text
Select Student
    ↓
Validate Student
    ↓
Select Room
    ↓
Check Room Exists
    ↓
Check Capacity / Availability
    ↓
Check Existing Active Allocation
    ↓
Create Allocation
    ↓
Update Room State
    ↓
Write Audit Record
    ↓
Update Quality Metrics
```

## Complaint Resolution Control

```text
Create Complaint
    ↓
Validate Complaint
    ↓
Record Complaint
    ↓
Assign Handler
    ↓
In Progress
    ↓
Resolution
    ↓
Verification
    ↓
Resolved / Closed
    ↓
Audit Record
```

## Control Evidence

Each important control should have evidence such as:

- validation result;
- database result;
- audit log;
- test result;
- error/bug record where applicable.
