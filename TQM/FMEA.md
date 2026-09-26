# FMEA — Initial Risk Analysis

**RPN = Severity × Occurrence × Detection**

Ratings will be reviewed using actual project/test evidence.

| Process | Failure Mode | Effect | Cause | Current/Planned Control | S | O | D | RPN | Action |
|---|---|---|---|---|---:|---:|---:|---:|---|
| Room Allocation | Occupied room allocated | Incorrect allocation | Availability not checked | Strict validation + DB control | 9 | 4 | 3 | 108 | Add pre-allocation validation |
| Room Allocation | Duplicate active allocation | Student linked incorrectly | Existing allocation not checked | Business rule + constraint | 9 | 3 | 3 | 81 | Block duplicate allocation |
| Student Registration | Duplicate student | Inaccurate records | Duplicate ID accepted | UNIQUE constraint + validation | 7 | 4 | 2 | 56 | Reject duplicate |
| Complaint | Complaint not tracked | Customer issue may be missed | Missing workflow/status | Required status + monitoring | 8 | 4 | 4 | 128 | Add controlled complaint workflow |
| Application | Unhandled exception | Application interruption | Missing exception handling | Central exception handling | 9 | 3 | 5 | 135 | Add controlled exception handler |
| Application | Error not logged | Difficult diagnosis | Missing logging | Structured error logger | 7 | 4 | 6 | 168 | Record required error fields |

## Note

These are **initial planning ratings**, not measured production results. They must be reviewed and updated when actual testing and defect data become available.
