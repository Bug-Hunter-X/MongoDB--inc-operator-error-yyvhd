# MongoDB $inc operator error
This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is designed to increment a numeric field by a specified value.  However, if a string is provided as the increment value, it will result in an error or unexpected behavior.

## Bug
The provided JavaScript code attempts to increment the `counter` field by the string '1'. This is incorrect; the increment value should be a number.

## Solution
The corrected code uses a numeric value (1) for the increment operation, correctly updating the `counter` field.