# MongoDB $inc Operator Error
This example demonstrates a common error when using the `$inc` operator in MongoDB updates.  The `$inc` operator is designed to increment a numeric field by a given value.  However, providing a string value instead of a number will lead to incorrect behavior.  This repository contains the buggy code and its corrected version.

## Bug Description
The original code attempts to increment the 'age' field by '2', which is a string instead of a number. This causes an error or unexpected results.  The corrected code demonstrates the proper use of the `$inc` operator with a numeric value.