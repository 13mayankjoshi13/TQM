# Testing Strategy

Testing is a major part of the assigned Q09 — Reduce Bugs quality goal.

## Testing Levels

### Unit / Module Testing

Critical services and validation functions will be tested independently.

### Integration Testing

Interactions between UI, services and database will be tested.

### Negative Testing

Invalid inputs and invalid process conditions will be deliberately tested.

### Regression Testing

Previously fixed defects will be retested after relevant changes.

## Test Record

Each test should record:

- Test ID
- Requirement ID
- Module
- Input
- Expected result
- Actual result
- Status
- Defect ID, if applicable

## Initial Test Areas

| Test Area | Example |
|---|---|
| Validation | Empty required field |
| Student | Duplicate registration number |
| Room | Invalid capacity |
| Allocation | Allocate occupied room |
| Complaint | Invalid complaint status |
| Exception handling | Simulated database failure |
| Error logging | Verify required log fields |
| Bug tracker | Create and resolve a test defect |
| Audit | Verify important action creates audit record |
