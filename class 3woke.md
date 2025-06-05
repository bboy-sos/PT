### 3. Error Correction

**Task:** Fix errors in the following pseudocode:

**Original Pseudocode:**
```
INPUT hoursWorked
IF hoursWorked > 40 THEN
    overtimePay = (hoursWorked - 40) * 15
    totalPay = (40 * 10) + overtimePay
ELSE
    totalPay = hoursWorked * 10
OUTPUT totalPay
END
```

**Issues:**
- Missing `END IF`.
- `OUTPUT` is not properly aligned (should be after the IF-ELSE block).
- No `START`/`END`.

**Corrected Pseudocode:**
```
START
INPUT hoursWorked
IF hoursWorked > 40 THEN
    overtimePay = (hoursWorked - 40) * 15
    totalPay = (40 * 10) + overtimePay
ELSE
    totalPay = hoursWorked * 10
END IF
OUTPUT "Total pay: ", totalPay
END
```