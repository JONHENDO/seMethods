# USE CASE: 7 Update an Employee's Details

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want *to update an employee's details* so that *employee's details are kept up-to-date.*

### Scope

Company.

### Level

Primary task.

### Preconditions

Employee exists in the system. HR system is accessible. HR advisor has the correct updated information.

### Success End Condition

Employee’s details are updated in the system.

### Failed End Condition

Employee’s details are not updated or are incorrect.

### Primary Actor

HR Advisor.

### Trigger

Updated information about an employee is received by HR.

## MAIN SUCCESS SCENARIO

1. HR advisor receives updated information for an employee.
2. HR advisor logs into the HR system.
3. HR advisor locates the employee's existing record.
4. HR advisor updates the relevant fields (e.g., address, role, salary).
5. HR advisor saves the changes and confirms the update.

## EXTENSIONS

3. **Employee record not found**:
    1. HR advisor investigates and contacts relevant parties to resolve the issue.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0