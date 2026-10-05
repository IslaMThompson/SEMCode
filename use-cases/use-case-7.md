# USE CASE: 7 Update a given employees details
## CHARACTERISTIC INFORMATION
### Goal in Context
As an HR advisor I want to update an employee's details so that employee's details are kept up-to-date.

### Scope
Company.

### Level
Primary task.

### Preconditions
We know the employee. Database contains current employee details.

### Success End Condition
HR is able to update the employees details.

### Failed End Condition
Details are not updated.

### Primary Actor
HR Advisor.

### Trigger
A request for an employees details to be updated is sent to HR.

## MAIN SUCCESS SCENARIO
1. Finance request details of a given employee be updated.
2. HR advisor captures employees new details.
3. HR advisor updates the employee with the new details.

## EXTENSIONS
Employee does not exist:
HR advisor informs finance no employee exists.

## SUB-VARIATIONS
None.

## SCHEDULE
DUE DATE: Release 1.0