# Quality Monitoring

## Monitoring Sources

The application will eventually produce structured quality evidence from:

- validation failures;
- exceptions;
- module test results;
- bug tracker;
- error logs;
- audit logs;
- room allocation events;
- complaint status.

## Planned Metrics

| Metric | Source | Target |
|---|---|---|
| Confirmed defects recorded | Bug tracker | 100% |
| Detected system errors logged | Error log | 100% |
| Invalid-input test cases passed | Module tests | 100% |
| Critical modules tested | Test records | 100% |
| Invalid room allocations accepted | Allocation tests | 0 |
| Complaints without status | Complaint records | 0 |

## Monitoring Principle

Do not create fake quality results.

The project will first define the metric, then collect actual data from tests and application activity, and finally analyze the resulting evidence.
