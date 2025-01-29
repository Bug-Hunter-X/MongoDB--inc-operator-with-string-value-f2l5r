# MongoDB $inc Operator with String Value
This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The error occurs when a string value is used instead of a number to increment a field.

## Bug Description:
The provided code attempts to increment a counter field using the `$inc` operator. However, it uses a string ("1") instead of a number (1).  This results in an unexpected behavior, with the counter field not being incremented correctly. This can lead to data inconsistencies and unpredictable application behavior.

## Solution:
The solution involves using an integer instead of a string when incrementing with the `$inc` operator. This ensures the correct numerical addition and prevents unexpected issues.
