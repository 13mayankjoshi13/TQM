# Process Map

## Main Hostel Process

```mermaid
flowchart TD
    A[Student / Staff Request] --> B[Enter Information]
    B --> C[Strict Validation]
    C -->|Invalid| D[Show Corrective Message]
    D --> B
    C -->|Valid| E[Business Rule Check]
    E -->|Rule Violation| D
    E -->|Valid| F[Database Transaction]
    F --> G[Audit Log]
    G --> H[Quality Monitoring]
    F -->|Exception| I[Exception Handler]
    I --> J[Error Log]
    J --> K[Bug Investigation]
```

## Room Allocation

Input → Validation → Availability Check → Allocation → Audit → Monitoring

## Complaint Resolution

Complaint → Validation → Assignment → Investigation → Resolution → Verification → Closure → Monitoring
