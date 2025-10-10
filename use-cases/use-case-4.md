# USE CASE: 1 Produce a Report on the Salary of All Employees

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want *to produce a report on the salary of all employees* so that *I can support financial reporting of the organisation.*
### Scope

Company.

### Level

Primary task.

### Preconditions

Database contains current employee salary data.


### Success End Condition# USE CASE: 2 Produce a Report on the Salary of Employees by Role

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want *to produce a report on the salary of employees of a given role* so that *I can support financial reporting of the organisation.*

### Scope

Company.

### Level

Primary task.

### Preconditions

Database contains current employee salary data and role classifications.

### Success End Condition

A report filtered by employee role is available for HR to provide to finance.

### Failed End Condition

No report is produced or the report is incorrect.

### Primary Actor

HR Advisor.

### Trigger

A request for role-specific salary information is sent to HR.

## MAIN SUCCESS SCENARIO

1. Finance requests salary information for employees of a specific role.
2. HR advisor accesses the database to retrieve current salary data filtered by the requested role.
3. HR advisor compiles a report with the salary details of employees in the specified role.
4. HR advisor provides the report to the finance department.

## EXTENSIONS

2. **Database access fails**:
    1. HR advisor reports the issue to IT and informs finance of the delay.

3. **Requested role does not exist or has no associated employees**:
    1. HR advisor informs finance that no data is available for the specified role.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0