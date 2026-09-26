# Customer Requirements

## 1. Project Information

**Project Name:** Hostel Management System
**Student:** Mayank Joshi
**Course:** BBAT104 — Fundamentals of TQM
**Academic Session:** 2026–27

---

## 2. Who Is the Customer?

The **primary customer** of the Hostel Management System is the **Hostel Administration / Hostel Warden**.

The hostel administration is responsible for managing hostel rooms, student records, room allocation and complaints. Therefore, the system should support them in performing these activities accurately and efficiently.

### Other Stakeholders

* Hostel Warden
* Hostel Administrator
* Hostel Staff
* Students / Hostellers
* System Administrator

### Difference Between Customer and Users

The **customer** is the person or organization whose operational requirements the system is designed to satisfy.

The **users** are the people who interact with the system.

For this project:

**Primary Customer:** Hostel Administration / Hostel Warden

**Primary Users:** Hostel Warden, Hostel Staff and System Administrator

**Other Stakeholders:** Students / Hostellers

---

# 3. Customer Problems

The customer may face the following operational problems:

1. Difficulty maintaining student records manually.
2. Difficulty identifying available and occupied rooms.
3. Possibility of assigning the same room incorrectly.
4. Difficulty tracking room allocations.
5. Difficulty monitoring hostel complaints.
6. Complaints may remain unresolved or untracked.
7. Manual data entry can introduce errors.
8. Important activities may not have a proper history.
9. Finding specific student or room information may take time.
10. There may be limited information available for identifying recurring problems.

---

# 4. Customer Requirements

The following requirements have been defined from the customer's operational needs.

| ID    | Customer Requirement                                                 | Measurement                          | Target                     | Verification               |
| ----- | -------------------------------------------------------------------- | ------------------------------------ | -------------------------- | -------------------------- |
| CR-01 | The system shall allow hostel staff to register student records.     | Valid student records created        | 100% of valid submissions  | Registration test          |
| CR-02 | The system shall prevent duplicate student records.                  | Duplicate records accepted           | 0                          | Duplicate-entry test       |
| CR-03 | The system shall maintain hostel room information.                   | Room records available               | 100%                       | Room module testing        |
| CR-04 | The system shall display room availability.                          | Correct availability status          | 100%                       | Room status testing        |
| CR-05 | The system shall prevent duplicate room allocation.                  | Duplicate allocations accepted       | 0                          | Allocation validation test |
| CR-06 | The system shall validate room allocation before saving it.          | Invalid allocations prevented        | 100%                       | Negative test cases        |
| CR-07 | The system shall allow authorized users to manage complaints.        | Valid complaints recorded            | 100%                       | Complaint module testing   |
| CR-08 | The system shall maintain complaint status.                          | Complaints having valid status       | 100%                       | Complaint status test      |
| CR-09 | The system shall allow users to identify unresolved complaints.      | Unresolved complaints visible        | 100%                       | Complaint filtering test   |
| CR-10 | The system shall maintain audit records for important operations.    | Important operations logged          | 100%                       | Audit-log verification     |
| CR-11 | The system shall prevent invalid data from being stored.             | Invalid records accepted             | 0                          | Validation testing         |
| CR-12 | The system shall provide understandable error messages.              | User errors with meaningful feedback | 100%                       | Error-handling tests       |
| CR-13 | The system shall record system errors for investigation.             | Detected system errors logged        | 100%                       | Error-log verification     |
| CR-14 | The system shall provide search/filter functionality.                | Required records retrievable         | 100% of defined test cases | Search testing             |
| CR-15 | The system shall provide quality-related information for monitoring. | Defined quality metrics available    | 100%                       | Quality dashboard testing  |

---

# 5. Customer Expectations

The customer expects the system to be:

### Accurate

The system should maintain correct student, room, allocation and complaint information.

### Reliable

Important operations should not unexpectedly fail or lose information.

### User-Friendly

Users should be able to understand and operate the system without unnecessary complexity.

### Error-Resistant

The system should prevent incorrect information wherever possible before it reaches the database.

### Traceable

Important actions should be recorded through audit logs.

### Measurable

The system should provide data that can be used to monitor quality.

### Maintainable

The application should have a well-organized folder and module structure so that future changes can be made safely.

---

# 6. Customer Requirements and TQM

The requirements will be connected with TQM concepts throughout development.

| Customer Need               | TQM Concept                | Planned System Response            |
| --------------------------- | -------------------------- | ---------------------------------- |
| Accurate room allocation    | Poka-Yoke                  | Allocation validation              |
| No duplicate allocation     | Error Prevention           | Database + application constraints |
| Easy complaint tracking     | Customer Focus             | Complaint management               |
| Traceability                | Monitoring                 | Audit logs                         |
| Fewer software errors       | Quality Assurance          | Validation and testing             |
| Identify recurring problems | Fact-Based Decision Making | Defect logs and quality metrics    |
| Control hostel processes    | Process Control            | Defined process workflows          |
| Continuous improvement      | PDCA                       | Quality monitoring and improvement |

---

# 7. Measurable Customer Satisfaction Indicators

The following indicators will be monitored as the project develops:

* Number of duplicate allocation attempts
* Number of invalid records rejected
* Number of complaints registered
* Number of open complaints
* Number of resolved complaints
* Complaint resolution time
* Number of system errors
* Number of software defects
* Audit log coverage
* Successful room allocations
* Failed room allocation attempts

These measurements will later be connected to the TQM quality monitoring system.

---

# 8. Requirement Traceability

Each important customer requirement will later be connected to:

**Customer Requirement → Quality Objective → Software Feature → TQM Concept → Test Case → Evidence**

Example:

**CR-05: Prevent duplicate room allocation**

↓

**Quality Objective: Zero duplicate room allocations**

↓

**Feature: Room allocation validation**

↓

**TQM Concept: Poka-Yoke / Error Prevention**

↓

**Test Case: Attempt allocation of an occupied room**

↓

**Evidence: Test result + audit/error record**

---

# 9. Requirement Status

| Requirement Range       | Current Status |
| ----------------------- | -------------- |
| CR-01 – CR-15           | Defined        |
| Quality mapping         | Defined        |
| Software implementation | Pending        |
| Testing                 | Pending        |
| Quality measurement     | Pending        |
| Final verification      | Pending        |

This document will be updated as the software requirements become more detailed during development.
