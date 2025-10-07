# USE CASE: 6 View an Employee's Details

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want *to view an employee's details* so that *the employee's promotion request can be supported.*

### Scope

Company.

### Level

Primary task.

### Preconditions

Employee exists in the system. HR system is accessible.

### Success End Condition

Employee's details are retrieved and available for promotion review.

### Failed End Condition

Employee's details are not retrieved.

### Primary Actor

HR Advisor.

### Trigger

A promotion request is submitted for an employee.

## MAIN SUCCESS SCENARIO

1. HR advisor receives a promotion request for an employee.
2. HR advisor accesses the HR system.
3. HR advisor searches for the employee’s record.
4. HR advisor views and verifies the employee’s details (e.g., role, tenure, performance data).
5. HR advisor provides the relevant details to the promotion review process.

## EXTENSIONS

3. **Employee record not found**:
    1. HR advisor informs relevant parties and investigates the missing data.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0