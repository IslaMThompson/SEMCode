# USE CASE: 6 Produce a Report on a given employees details
## CHARACTERISTIC INFORMATION
### Goal in Context
As an HR advisor I want to view an employee's details so that the employee's promotion request can be supported.

### Scope
Company.

### Level
Primary task.

### Preconditions
We know the employee. Database contains current employee details.

### Success End Condition
A report is available for HR to give to finance.

### Failed End Condition
No report is produced.

### Primary Actor
HR Advisor.

### Trigger
A request for an employees details is sent to HR.

## MAIN SUCCESS SCENARIO
1. Finance request details of a given employee.
2. HR advisor captures employee identity to get their details.
3. HR advisor extracts current employee details for the given employee.
4. HR advisor provides report to finance.

## EXTENSIONS
Employee does not exist:
HR advisor informs finance no employee exists.

## SUB-VARIATIONS
None.

## SCHEDULE
DUE DATE: Release 1.0