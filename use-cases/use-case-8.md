# USE CASE: 11 Delete an Employee's Details

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want *to delete an employee's details* so that *the company is compliant with data retention legislation.*

### Scope

Company.

### Level

Primary task.

### Preconditions

Employee has left the organisation. Retention period has expired. HR system is accessible.

### Success End Condition

Employee’s details are securely deleted from the system in accordance with legislation.

### Failed End Condition

Employee’s details are not deleted or are deleted prematurely.

### Primary Actor

HR Advisor.

### Trigger

Data retention period for a former employee has ended.

## MAIN SUCCESS SCENARIO

1. HR advisor identifies that the data retention period for an employee has expired.
2. HR advisor accesses the HR system.
3. HR advisor locates the employee’s record.
4. HR advisor confirms eligibility for deletion based on retention policy.
5. HR advisor deletes the employee’s details from the system.
6. Deletion is logged for audit purposes.

## EXTENSIONS

3. **Employee record cannot be found or deletion fails**:
    1. HR advisor contacts IT or system administrator for support.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0