## Group Activity: Real-World Scenario
## Task:
## In pairs, design pseudocode and a flowchart for a program ## that determines a gym membership fee based on age.

## Membership Fee Rules:
## $30/month: Age ≥ 18 and not a senior (age < 65)
## $20/month: Senior (age ≥ 65) or student (age 16–22)
## $0/month: Under 16 (free junior membership)
## Example Pseudocode
```
START
INPUT age
IF age < 16 THEN
    OUTPUT "Free junior membership"
ELSE IF (age >= 16 AND age <= 22) OR (age >= 65) THEN
    OUTPUT "Membership fee: $20"
ELSE
    OUTPUT "Membership fee: $30"
END IF
END
```