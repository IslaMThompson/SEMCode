# USE CASE: 8 Delete a given employees details
## CHARACTERISTIC INFORMATION
### Goal in Context
As an HR advisor I want to delete an employee's details so that the company is compliant with data retention legislation.

### Scope
Company.

### Level
Primary task.

### Preconditions
We know the employee. Database contains current employee details.

### Success End Condition
HR is able to delete the employees details.

### Failed End Condition
Details are not deleted.

### Primary Actor
HR Advisor.

### Trigger
A request for an employees details to be details is sent to HR.

## MAIN SUCCESS SCENARIO
1. Finance request details of a given employee be deleted.
2. HR advisor captures employees identity.
3. HR advisor deletes the employees details.

## EXTENSIONS
Employee does not exist:
HR advisor informs finance no employee exists.

## SUB-VARIATIONS
None.

## SCHEDULE
DUE DATE: Release 1.0