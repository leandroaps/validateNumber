# validateNumber
This snippet can be used to check whether a value is a number.

```
const validateNumber = n => !isNaN(parseFloat(n)) && isFinite(n) && Number(n) == n;
```

**Usage:**
```
validateNumber('10'); // true
```
