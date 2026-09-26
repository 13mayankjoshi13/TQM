# Error Prevention at Source

## Purpose

Error prevention should happen before incorrect data reaches the database whenever possible.

## Prevention Layers

1. UI-level validation
2. Business-rule validation
3. Database constraints
4. Transaction handling
5. Automated tests
6. Error and defect monitoring

## Examples

### Student Registration

Prevent:

- empty required fields;
- duplicate registration numbers;
- invalid phone numbers;
- invalid formats.

### Room Allocation

Prevent:

- allocation to a non-existent room;
- allocation to an occupied/full room;
- duplicate active allocation;
- invalid student selection.

### Complaint

Prevent:

- empty complaint title/description;
- invalid status transitions;
- invalid user actions.

## TQM Connection

This applies the Poka-Yoke principle from the course requirements: prevent errors at the point of entry rather than depending only on later inspection.
