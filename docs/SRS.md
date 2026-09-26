# Software Requirements Specification

## 1. Introduction

The Hostel Management System is a software application for managing hostel-related records and workflows while applying TQM principles.

## 2. Scope

### In Scope

- User authentication
- Student records
- Room records
- Room allocation
- Complaint records
- Validation
- Exception handling
- Module testing
- Bug tracking
- Error logging
- Audit logging
- Quality monitoring

### Out of Scope for the Initial Version

- Online payment gateway
- Biometric integration
- External hostel ERP integration
- Mobile application
- Automated attendance hardware

These may be considered separately only if required later.

## 3. Functional Requirements

| ID | Requirement |
|---|---|
| FR-01 | The system shall allow authorized users to log in. |
| FR-02 | The system shall allow authorized users to manage student records. |
| FR-03 | The system shall allow authorized users to manage room records. |
| FR-04 | The system shall validate room availability before allocation. |
| FR-05 | The system shall prevent invalid room allocations. |
| FR-06 | The system shall allow complaints to be recorded and tracked. |
| FR-07 | The system shall handle defined application exceptions in a controlled manner. |
| FR-08 | The system shall maintain an internal error log for detected system errors. |
| FR-09 | The system shall maintain a bug tracker for confirmed software defects. |
| FR-10 | The system shall provide module tests for critical modules. |
| FR-11 | The system shall maintain audit records for defined important operations. |
| FR-12 | The system shall provide quality monitoring information. |

## 4. Non-Functional Requirements

- Usability: common operations should have clear labels and feedback.
- Reliability: failures should be handled without uncontrolled crashes where recovery is possible.
- Maintainability: modules should have clear responsibilities.
- Traceability: important actions and quality events should be recorded.
- Data integrity: database constraints and application validation should work together.
- Testability: critical modules should be independently testable.

## 5. Assigned Quality Goal

**Q09 — Reduce Bugs**

The five required quality-goal features are:

1. Exception Handling
2. Strict Validation
3. Module Tests
4. Bug Tracker
5. Error Logs
