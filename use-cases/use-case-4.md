# USE CASE: 4 Produce a Report on the Salary of Employees of a Given Role

## CHARACTERISTIC INFORMATION

### Goal in Context

As an *HR advisor* I want *to produce a report on the salary of employees of a given role* so that *I can support financial reporting of the organisation.*

### Scope

Company.

### Level

Primary task.

### Preconditions

The role is known. Database contains current employee salary data by role.

### Success End Condition

A report is available for the HR advisor to support organisation-wide financial reporting.

### Failed End Condition

No report is produced.

### Primary Actor

HR Advisor.

### Trigger

A request or requirement for organisational financial reporting arises.

## MAIN SUCCESS SCENARIO

1. HR advisor initiates a request to access salary information by employee role.
2. HR advisor specifies the role for which salary data is needed.
3. HR advisor retrieves current salary data for all employees in the specified role.
4. HR advisor compiles and reviews the report.
5. Report is used for organisation-wide financial reporting.

## EXTENSIONS

3. **Role-specific data is incomplete or unavailable**:
    1. HR advisor contacts relevant department or IT support to resolve the data issue.

## SUB-VARIATIONS

None.

## SCHEDULE

**DUE DATE**: Release 1.0
