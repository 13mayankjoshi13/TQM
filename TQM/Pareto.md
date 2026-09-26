# Pareto Analysis

Pareto analysis will be generated from the actual defect log.

## Planned Input

`TQM/data/defect_log.csv`

## Planned Categories

- Validation
- Exception Handling
- Database
- Room Allocation
- Complaint Management
- Authentication
- UI
- Other

## Method

1. Count defects by category.
2. Sort categories by frequency.
3. Calculate cumulative percentage.
4. Generate a Pareto chart using Python/Matplotlib.
5. Identify the categories contributing most to the observed defects.
6. Use the result to prioritize improvement work.

No final Pareto conclusion should be written until actual defect data has been collected.
